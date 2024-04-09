<h1 align="center">360QuakeSpider_GO版本</h1>
<p align="center">
    <a href="https://github.com/wanswu/360quakeSpider_GO/releases"/><img src="https://img.shields.io/github/downloads/wanswu/360quakeSpider_GO/total"/>
    <a href="https://github.com/wanswu/360quakeSpider_GO/graphs/contributors"/><img src="https://img.shields.io/github/contributors-anon/wanswu/360quakeSpider_GO"/>
    <a href="https://github.com/wanswu/360quakeSpider_GO/releases/"/><img src="https://img.shields.io/github/release/wanswu/360quakeSpider_GO"/>
    <a href="https://github.com/wanswu/360quakeSpider_GO/issues"/><img src="https://img.shields.io/github/issues-raw/wanswu/360quakeSpider_GO"/>
</p>

---


# 版本历史
## 2024.3.13
- [x] 1.绕过1w条数据的限制（不太稳定）
## 2024.1.17

目前完成的功能：

- [x] 1.数据存储（txt）


# 使用方法
在[releases](https://github.com/wanswu/360quakeSpider_GO/releases)中下载对应系统版本

第一次执行会生成配置文件（config.yaml）
在quake的Cookie中找到`cert_common`的值，并粘贴至`config.yaml`中
![img.png](doc/img.png)
```shell
./360quakeSpider_GO -k '搜索语法'
```

# `PS：代码写的和屎一样，就不发了`

[![Stargazers over time](https://starchart.cc/wanswu/360quakeSpider_GO.svg?variant=adaptive)](https://starchart.cc/wanswu/360quakeSpider_GO)
