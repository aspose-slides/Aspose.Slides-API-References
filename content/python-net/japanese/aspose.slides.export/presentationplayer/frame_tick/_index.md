---
title: frame_tick event
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick イベント
frame_tick イベント。

[`PresentationAnimationsGenerator`](/slides/python-net/ja/aspose.slides.export/presentationanimationsgenerator) によって作成されたアニメーションの各フレームがプレーヤーによって生成されるときに発生します。

### 定義:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/ja/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/ja/aspose.slides.export/frametickeventargs) |  |

### 参照
* クラス [`FrameTickEventArgs`](/slides/python-net/ja/aspose.slides.export/frametickeventargs)
* クラス [`PresentationAnimationsGenerator`](/slides/python-net/ja/aspose.slides.export/presentationanimationsgenerator)
* クラス [`PresentationPlayer`](/slides/python-net/ja/aspose.slides.export/presentationplayer)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)