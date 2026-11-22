---
title: frame_tick event
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick 事件
frame_tick 事件。

当由 [`PresentationAnimationsGenerator`](/slides/python-net/zh/aspose.slides.export/presentationanimationsgenerator) 创建的动画的每一帧被播放器生成时发生。

### 定义:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/zh/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/zh/aspose.slides.export/frametickeventargs) |  |

### 另见
* 类 [`FrameTickEventArgs`](/slides/python-net/zh/aspose.slides.export/frametickeventargs)
* 类 [`PresentationAnimationsGenerator`](/slides/python-net/zh/aspose.slides.export/presentationanimationsgenerator)
* 类 [`PresentationPlayer`](/slides/python-net/zh/aspose.slides.export/presentationplayer)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)