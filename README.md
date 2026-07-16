# LOTUS ForMe 车机自检

一个无需下载、直接在车机浏览器中运行的静态只读检测页。

- 所有检测都在浏览器本地执行。
- 页面没有外部脚本、字体、图片或统计服务。
- 页面不会上传检测结果。
- 已提供腾讯 EdgeOne Pages 国内首选地址和 GitHub Pages 备用地址。

## 在线地址

- 国内首选（腾讯 EdgeOne Pages）：<https://mcp.edgeone.site/share/6GrtaRTdfTF43fVpnwwlM>
- GitHub Pages 备用：<https://shupivot.github.io/lotus-forme-carcheck/>

页面安全策略只允许运行经过哈希校验的检测脚本，并设置 `connect-src 'none'` 阻止页面主动向外发送检测结果。托管平台仍可能记录普通 HTTP 访问日志，请勿在页面记录框填写 VIN、电话、地址或账号等隐私信息。
