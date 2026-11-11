# muskill

视频创作相关的 AI skills，每个目录包含一份 `SKILL.md`。

| Skill | 用途 |
| --- | --- |
| [muse-video-prompt-director](muse-video-prompt-director/SKILL.md) | 根据时长、主题和参考素材编写 Muse Video 提示词，支持按每段最多 10 秒拆分长视频。 |
| [cartoon-audio-short](cartoon-audio-short/SKILL.md) | 从选题、脚本与配音规划竖屏动画短片的制作流程。 |

## 使用说明

在支持 skills 的工具中加载所需目录，或直接阅读对应的 `SKILL.md`。

`cartoon-audio-short` 已附用户提供的 [cartoon-short-kit 工具包](cartoon-audio-short/kit/)，包含引擎、制作工具和 soldier 示例。工具包按原文件保存。

当前仍有以下运行限制：

- 缺少 skill 要求的 `mix.py` 混音脚本。
- Three.js 与 `toon.ts` 由初始化脚本联网获取；运行环境需另行准备。
- 初始化脚本未将 `finish.sh` 复制到项目目录，并会向 `kit/vendor/` 写入文件，与 skill 中的部分说明尚不一致。

本次仅核对文件完整性，未执行初始化或视频渲染流程。
