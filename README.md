# tBox 源配置（自托管副本）

> 本仓库是 [tBox](https://github.com/Hululu007/tBox) 源配置与解析脚本的**自托管副本**。所有 JSON 里的 `ext` 解析脚本链接已改写为指向本仓库（`mlzbest/tbox-sources`），不再依赖原作者服务器，避免作者删库 / 改链导致失效。

## 源文件

| 文件 | 用途 |
|---|---|
| `music.json` | 听书 / 听歌源 |
| `new.json` | 影视点播源（iOS 推荐） |
| `安卓new.json` | 影视点播源（安卓优化） |
| `配置.json` | 综合配置（含 JS 解析器、soup / xbiu / xpath 规则） |

解析脚本目录：`js/`、`newjs/`、`soup/`、`xbiu/`、`xbiubiu/`、`xpath/`。

## 在 tBox 中导入（iOS / 安卓）

打开 tBox → 设置 → 配置 / 源管理 → 粘贴以下链接（或导入本地文件）：

- 影视点播源（iOS）：`https://raw.githubusercontent.com/mlzbest/tbox-sources/main/new.json`
- 听书听歌源：`https://raw.githubusercontent.com/mlzbest/tbox-sources/main/music.json`
- 安卓端视频源：`https://raw.githubusercontent.com/mlzbest/tbox-sources/main/%E5%AE%89%E5%8D%93new.json`
- 综合配置：`https://raw.githubusercontent.com/mlzbest/tbox-sources/main/%E9%85%8D%E7%BD%AE.json`

> 搜索影片之前，建议关闭不常用的站源以提升速度。

## 温馨提示（来自上游）

- 夸克网盘需最低 88 会员观看；UC 网盘 + 天翼云盘无需会员。网盘限制：夸克 + UC 切换剧集建议间隔 ≥10 秒（播放网盘资源时，设置中调整播放器缓存为 128M）。
- 天翼云盘 cookie 有 IP 验证，切换 IP 后失效，且 IPv4 / IPv6 cookie 不可混用，建议在电信 WiFi（IPv4）环境下使用。
- 如某站点无返回，请在设置中打开一次该站点（有时需校验）。

## 免责声明

本仓库仅托管**配置与解析脚本**，不提供任何影视 / 音频资源。所有内容由源站提供，仅供个人学习与技术研究，请遵守当地法律法规。
