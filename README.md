# Revhook Frida

[![License: MIT](https://img.shields.io/github/license/mob1254/revhook-frida)](LICENSE)

> Revhook 配套的 Magisk / KernelSU Frida 模块

## 简介

通过 Zygisk / Riru 把 Frida Gadget 注入到目标应用，给 [Revhook](https://github.com/mob1254/Revhook) 用。运行目录仍是 `/data/local/tmp/JsxposedXSo`。

本项目由 AI 基于 [jsxposedx-frida](https://github.com/dugongzi/jsxposedx-frida) 二改，上游是 [ZygiskFrida](https://github.com/lico-n/ZygiskFrida)。

## 使用方法

1. 在 Magisk 或 KernelSU 里安装本模块并启用
2. 重启
3. 打开 Revhook，首页 Frida 应变为已激活

不要和旧的 JsxposedX / ZygiskFrida 模块同时开。

## 问题反馈

走 [Revhook Issue](https://github.com/mob1254/Revhook/issues)。

## 致谢

感谢 [ZygiskFrida](https://github.com/lico-n/ZygiskFrida) 与 [jsxposedx-frida](https://github.com/dugongzi/jsxposedx-frida)。

## 开源协议

MIT，见 [LICENSE](LICENSE)。
