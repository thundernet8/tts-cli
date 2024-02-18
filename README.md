# tts-cli
将[edge-tts](https://github.com/rany2/edge-tts)封装并构建为单个可执行文件（避免移动使用时的依赖丢失问题），并通过基于命令行的跨编程语言交互来实现[VoxScripts-隐私优先的媒体转录、字幕翻译、语音翻译 PC 软件](https://voxscripts.com)的部分功能。

## Test
可执行文件见 Github Actions

```bash
./edge-tts --voice zh-CN-XiaoyiNeural --text "如果您需要建立一个网站，购买域名是最基础的一步。不论是个人用户还是企业用户，您只有完成域名的注册和认证，才能让用户访问您搭建的网站。本文主要介绍如何快速进行域名注册和实名认证" --write-media test.mp3 --write-subtitles test.vtt
```
