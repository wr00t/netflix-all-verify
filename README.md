# netflix-all-verify

NetFlix 批量检测，golang 编写

Netflix 的大规模封锁,网上的 Netflix 检测脚本只有本地检测的功能, 因而诞生了本项目

本项目基于 [netflix-verify](https://github.com/sjlleo/netflix-verify) 修改,增加了对批量检测的功能

## 使用方法

1. 源码运行（已经存在 go 运行环境）

克隆源码，在终端运行：
```bash
$ go run main.go 'clash 订阅 url'
```
2. 使用编译好的程序运行

从 [Releases](https://github.com/wr00t/netflix-all-verify/releases/latest) 页面下载编译好的程序，在终端运行：
```bash
./netflix-all-verify 'clash 订阅 url'
```

## 未来工作

- [x] 集成clash，不依靠客户端
- [x] 落地机ip检测,检测复用ip
- [x] 导出为Excel
- [ ] 内置订阅转换,便于不同订阅地址的使用
- [ ] web界面
- [ ] 结果导出图片化
- [ ] 测速

## 感谢

1. 感谢 [netflix-verify](https://github.com/sjlleo/netflix-verify)
2. 感谢 [clash](https://github.com/Dreamacro/clash)