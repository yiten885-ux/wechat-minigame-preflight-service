# 微信小游戏上线前工程快检

一个工程一次快检，首三单 **人民币 99 元**，收到脱敏材料后 24 小时内交付 PDF 或 Markdown 风险报告，并含一次文字答疑。

**服务说明页：** <https://yiten885-ux.github.io/wechat-minigame-preflight-service/>

本服务面向准备预览、上传或提审，但不确定工程还缺什么的微信小游戏开发者。原生 JavaScript / Canvas 项目优先；Cocos、Unity 或复杂服务端项目需要先确认范围。

## 检查范围

1. 工程入口、资源路径和包体风险；
2. 微信容器不兼容 API；
3. 隐私 API、用户数据、本地存档与清除路径；
4. 激励视频成功、失败、取消与重复回调风险；
5. 安全区、窄屏、触控与恢复路径；
6. 本地构建、开发者工具、官方预览、真机、上传、提审和上线证据是否混淆；
7. 最先应修复的三个 P0/P1 问题。

## 交付物

- 一页结论摘要；
- 逐项风险、证据定位、优先级和修复建议；
- 一次文字答疑。

[查看虚构匿名示例](./sample-report.md)。示例只用于展示报告结构，不是真实客户案例，也不代表微信官方审核结果。

## 咨询与下单

请先[新建服务咨询 Issue](../../issues/new?template=service-inquiry.yml)，只填写项目类型、技术栈、当前阶段和最担心的问题。确认范围后再通过平台担保付款；未确认范围前不要付款。

公开 Issue 中不要上传源码、日志、截图或商业机密。需要检查时，仅提供脱敏压缩包、只读仓库或必要的脱敏截图。

## 隐私与安全

本服务不需要、也不会索取：

- 微信、GitHub、云平台或其他账号密码；
- AppSecret、API Key、访问令牌、Cookie、验证码；
- 身份证、营业执照原图或其他身份证明；
- 真实用户数据、聊天记录或支付资料。

如果材料中发现疑似凭据，会停止读取并要求重新提供脱敏副本。

## 服务边界

- 这是工程风险快检，不是微信官方审核；
- 不承诺包过审、上线时间、流量或收入；
- 99 元不包含代码修复、真机测试、备案、资质申请、后台代操作和正式提审；
- 缺少证据的项目会标记为“未知/未验证”，不会写成已通过；
- 一个订单只覆盖一个工程和一个明确版本。

## English summary

Pre-submission engineering risk review for one WeChat Mini Game project. Introductory price: CNY 99 for the first three orders. Delivery within 24 hours after sanitized materials are received. This is an independent engineering review, not an official WeChat audit or approval guarantee.
