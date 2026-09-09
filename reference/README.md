# 视频参考素材

此目录用于记录用户提供的参考影片与分析依据，不是网页运行资源，也不进入 GitHub Pages 发布包。

## 原始视频

[designed-by-apple-intention-1080p.mp4](video/designed-by-apple-intention-1080p.mp4)

- 原附件名：`designed_by_apple_-_intention (1080p).mp4`。
- 1920×1080，约 90.985333 秒，标称 23.976025 fps。
- 文件只重命名和移动，未转码、裁剪或去除音轨；网页实现不使用音频。
- 大小：11,782,627 字节。文件校验值见[素材清单](../docs/asset-manifest.json)。

## 联系表

全片总览来自每秒抽帧；重点转场来自追加的原始分辨率抽帧。联系表内 `frame-` / `cal-` 标签为分析时的源时间标签，当前仓库文件名统一采用时间码及画面主题。

- [overview-000s-023s.jpg](contact-sheets/overview-000s-023s.jpg)
- [overview-024s-047s.jpg](contact-sheets/overview-024s-047s.jpg)
- [overview-048s-071s.jpg](contact-sheets/overview-048s-071s.jpg)
- [overview-072s-090s.jpg](contact-sheets/overview-072s-090s.jpg)
- [detail-003.000s-015.000s-geometry.jpg](contact-sheets/detail-003.000s-015.000s-geometry.jpg)
- [detail-025.500s-027.500s-diagonal-wipe.jpg](contact-sheets/detail-025.500s-027.500s-diagonal-wipe.jpg)
- [detail-038.500s-041.750s-feel-burst.jpg](contact-sheets/detail-038.500s-041.750s-feel-burst.jpg)
- [detail-043.000s-047.500s-connection.jpg](contact-sheets/detail-043.000s-047.500s-connection.jpg)
- [detail-050.000s-053.500s-intention.jpg](contact-sheets/detail-050.000s-053.500s-intention.jpg)
- [detail-060.000s-067.000s-convergence.jpg](contact-sheets/detail-060.000s-067.000s-convergence.jpg)
- [detail-068.500s-071.500s-black-circle.jpg](contact-sheets/detail-068.500s-071.500s-black-circle.jpg)
- [detail-075.500s-082.500s-white-circles.jpg](contact-sheets/detail-075.500s-082.500s-white-circles.jpg)

## 精选关键帧

从已检查的参考帧中选取 24 张。`005.000s` 表示请求抽取的源视频第 5 秒；视频帧实际时间按其约 23.976 fps 的帧边界对齐，文件名不是逐帧测量精度声明。

部分早期概览帧为 640×360，追加精校帧为 1920×1080；下表列出实际尺寸，未将低分辨率帧放大冒充原始分辨率。

| 源时间（秒） | 画面 | 尺寸 |
| --- | --- | --- |
| 5.000 | [square](frames/005.000s-square.jpg) | 1920×1080 |
| 9.000 | [layered-geometry](frames/009.000s-layered-geometry.jpg) | 1920×1080 |
| 14.000 | [perfect-anything](frames/014.000s-perfect-anything.jpg) | 1920×1080 |
| 18.000 | [convenience](frames/018.000s-convenience.jpg) | 640×360 |
| 24.000 | [abundance](frames/024.000s-abundance.jpg) | 640×360 |
| 26.750 | [diagonal-wipe](frames/026.750s-diagonal-wipe.jpg) | 1920×1080 |
| 31.000 | [focus](frames/031.000s-focus.jpg) | 640×360 |
| 38.750 | [feel-question](frames/038.750s-feel-question.jpg) | 1920×1080 |
| 39.000 | [particle-burst](frames/039.000s-particle-burst.jpg) | 1920×1080 |
| 41.500 | [surprise](frames/041.500s-surprise.jpg) | 1920×1080 |
| 43.500 | [love](frames/043.500s-love.jpg) | 1920×1080 |
| 45.000 | [connection](frames/045.000s-connection.jpg) | 1920×1080 |
| 49.000 | [intention](frames/049.000s-intention.jpg) | 640×360 |
| 59.000 | [thousand-nos](frames/059.000s-thousand-nos.jpg) | 640×360 |
| 63.000 | [radial-network](frames/063.000s-radial-network.jpg) | 1920×1080 |
| 66.000 | [one-yes](frames/066.000s-one-yes.jpg) | 1920×1080 |
| 68.000 | [simplify](frames/068.000s-simplify.jpg) | 640×360 |
| 69.500 | [perfect](frames/069.500s-perfect.jpg) | 1920×1080 |
| 71.000 | [start-over](frames/071.000s-start-over.jpg) | 1920×1080 |
| 78.000 | [enhances-life](frames/078.000s-enhances-life.jpg) | 1920×1080 |
| 80.000 | [second-pulse](frames/080.000s-second-pulse.jpg) | 1920×1080 |
| 82.000 | [white-wipe](frames/082.000s-white-wipe.jpg) | 1920×1080 |
| 85.000 | [sign-work](frames/085.000s-sign-work.jpg) | 640×360 |
| 89.000 | [signature](frames/089.000s-signature.jpg) | 640×360 |

## 归档方式

已按用户选择保留联系表与精选关键帧，不提交所有 298 张独立视频抽帧。原视频始终是视觉基准，未归档的帧可从它重新提取。

[网页绘图预览](../docs/previews/README.md) 单独存放，用于区别原片画面与实现结果。全部入库素材的来源类别、时间码、尺寸和 SHA-256 位于 [`docs/asset-manifest.json`](../docs/asset-manifest.json)。
