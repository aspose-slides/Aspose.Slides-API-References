---
title: frame_tick event
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick 事件
frame_tick 事件。

當由 [`PresentationAnimationsGenerator`](/slides/python-net/zh-hant/aspose.slides.export/presentationanimationsgenerator) 建立的動畫的每一幀由播放器產生時發生。

### 定義：
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/zh-hant/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/zh-hant/aspose.slides.export/frametickeventargs) |  |

### 另見
* 類別 [`FrameTickEventArgs`](/slides/python-net/zh-hant/aspose.slides.export/frametickeventargs)
* 類別 [`PresentationAnimationsGenerator`](/slides/python-net/zh-hant/aspose.slides.export/presentationanimationsgenerator)
* 類別 [`PresentationPlayer`](/slides/python-net/zh-hant/aspose.slides.export/presentationplayer)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)