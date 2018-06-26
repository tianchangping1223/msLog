# Abstract
log for webView &amp; appWeb

A tool imitate the browser console on webView or webApp;


# example
[example](https://martin-bai.github.io/msLog/example/index.html)

![QR Code](/example/QRCode.jpg)

# use
```
var msLog = new MagicSquareLog();

msLog.log(11111); 
// 11111

msLog.log([1,2,3]);
// [1,2,3]

msLog.error(11111, "I am the log", {name: "msLog"}, [1,2,3]); 
//11111 I am the log {"name":"msLog"} [1,2,3]

```

# API

| name          | type           | defaultParams | description |
| ------------- | -------------  | ------------- | ----------- |
| log           | function       | ""            | default log function |
| error         | function       | ""            | the color of text is red |

# License
[MIT](https://opensource.org/licenses/MIT)
