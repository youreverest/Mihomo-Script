# Mihomo-Script
适用于Mihomo/Clash内核的覆写脚本

## 警告及免责声明

**本仓库所有内容禁止以任何形式转载分享至中国大陆任何平台，否则您将承担所有法律责任。**

**本资源仅供中华人民共和国全境以外且不持有中华人民共和国任何地区国籍者使用，若您符合上述任一条件，请立即退出，严禁任何形式的浏览、保存、使用或分享，否则一切法律责任及不利后果自负。**

**所有内容仅适用于合法国家或地区，本人不承担任何法律责任。**

## 🚀 Mihomo / Clash 智能订阅覆写脚本 (Fake-IP & 动态节点适配)

这是一个适用于 Clash / Mihomo / Verge 等客户端的 JS 覆写脚本（Parsers / Script / Profile Mixin）。

Script标准版脚本旨在**不破坏机场原有节点与策略组**的前提下，自动识别主代理策略组、配置高效的 Fake-IP DNS，并应用精简合理的分流规则。

Elite至尊版脚本支持**根据地区进行代理**的方案，舍弃了冗杂的第三方ruleset方案，分流方案完全调用预设外部资源，在各种软件及设备上兼容良好，性能损耗低，自动识别主代理策略组、配置高效的 Fake-IP DNS，并应用精简合理的分流规则。

本仓库覆写脚本主打只用机场的节点，无视机场提供的DNS配置以及分流规则，再也不用担心被机场提供的垃圾规则困扰了！！！

---

## 📲 适用软件

适用包括但不限于 Bettbox, FlClash, ClashMi, Clash Meta, Clash Verge, Open Clash 等使用Mihomo/Clash/Clash Meta或相关/相似内核的软件，Android, iOS, Harmony, Windows, MacOS, Linux, OpenWRT, iStore 等各种平台运行之软件/插件均适用。

## ✨ 核心特性

1. **🤖 智能策略组适配**：自动识别机场订阅中的主要代理策略组（如 `Proxy`、`节点选择`、`自动选择` 等），无需手动更改策略组名称。
2. **⚡ 高效 Fake-IP DNS**：优化 DNS 解析流程，使用 Fake-IP 模式极大地提升域名解析与连接建立速度。
3. **🛡️ 纯净分流规则**：
   - **局域网 & NTP（时间同步）**：强制直连，避免时间同步异常。
   - **广告拦截**：基础广告域名直接拒连（REJECT）。
   - **国内服务优化**：苹果国内域名、GEOIP CN 中国大陆 IP 自动直连。
   - **国外常用服务覆盖**：针对 Google、YouTube、Telegram、GitHub、Steam、OpenAI/ChatGPT、X (Twitter)、Microsoft 等服务精准走代理。
   - **安全兜底**：未命中的流量统一兜底至识别出的主代理策略组。

## 广告投放

请联系 https://t.me/A89899999

## 如何使用?
复制下列链接，在软件中选择从URL导入即可

**至尊版系列**：

⭐️⭐️⭐️⭐️⭐️ 推荐使用，正常更新

至尊自动选择版本:
https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script-EliteU.txt

至尊负载均衡版本:
https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script-EliteL.txt

至尊故障转移版本:
https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script-EliteF.txt

**其他版本：**

标准版：（除非重大BUG，否则不更新）https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script.txt

专业版：（除非重大BUG，否则不更新）
https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script-Pro.txt

极致版：（除非重大BUG，否则不更新）
https://raw.githubusercontent.com/youreverest/Mihomo-Script/refs/heads/main/Script-Ultra.txt

## 📄 开源许可

本项目遵循 [AGPL-3.0](LICENSE) 协议开源。
