# YApi 安装和配置


## 部署的环境

- 系统：`CentOS 7.4`
- 硬件要求：`1 GB RAM minimum`
- ip：`http://192.168.1.121`
- docker version：`17.12.1-ce, build 7390fc6`
- docker-compose version：`1.18.0, build 8dd22a9`

> 建议部署成 http 站点，因 chrome 浏览器安全限制，部署成 https 会导致测试功能在请求 http 站点时文件上传功能异常。--[来源](https://yapi.ymfe.org/devops.html)

## Docker 快速部署-方案1

- 推荐
- <https://github.com/fjc0k/docker-YApi>
- 特别注意点，记得把 YAPI_CLOSE_REGISTER=true 改为 false，不然无法让别人注册

## YApi 介绍

- 官网：<https://yapi.ymfe.org/index.html>
- Github：<https://github.com/YMFE/yapi>
- 官网在线演示：<http://yapi.demo.qunar.com/>
- 使用手册：<https://yapi.ymfe.org/usage.html>
