# Vercel 汉化 PRO (Vercel Chinese PRO)

Vercel用户界面汉化脚本,支持自动将Vercel网站界面翻译为中文。

> 原版仓库：https://github.com/liyixin21/vercel-chinese
>
> 基于原版修改：
>
> 1. 完善部分翻译
>
> 2. 增加部分句子翻译
>
> 3. 修复无法跳转安装的BUG


## 功能特性

- 实时翻译Vercel界面上的英文文本为中文
- 支持部署页面、仪表盘、设置、团队管理等所有主要界面
- 自动监听DOM变化,对动态加载的内容进行翻译
- 轻量级实现,不影响网站原有功能

## 安装方法

1. 首先需要安装用户脚本管理器扩展：
   - Chrome: 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/) 或 [ScriptCat](https://violentmonkey.github.io/)
   - Edge: 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/) 或 [ScriptCat](https://violentmonkey.github.io/)
   - Firefox: 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/) 或 [ScriptCat](https://violentmonkey.github.io/) 或 [Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/)
   - Safari: 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Userscripts](https://apps.apple.com/app/userscripts/id1463298887)
   - Opera: 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/)
   - Via 不需要安装插件
   - AdGuard 不需要安装插件
   - Gear 不需要安装插件
   - 使用Tampermonkey外其他插件出现的任何兼容问题概不负责

2. 点击下方链接安装脚本：
   - [从Greasy Fork安装（建议）](https://greasyfork.org/zh-CN/scripts/546025-vercel-%E6%B1%89%E5%8C%96-pro)
   - [安装脚本（Github）](https://github.com/quan-ge/vercel-chinese-pro/raw/main/vercel-chinese.user.js)
   - [Github镜像加速](https://proxy.pipers.cn/https://github.com/quan-ge/vercel-chinese-pro/raw/main/vercel-chinese.user.js)

4. 脚本会自动在Vercel网站界面启用,刷新页面即可看到汉化效果

## 已知问题

- 某些动态生成的内容可能不会被立即翻译,刷新页面即可解决
- 少量专业术语或特殊文本可能未被翻译,欢迎提交PR补充
- 新添加翻译可能不准确

## 免责声明

本项目不隶属于Vercel,仅供学习交流。
