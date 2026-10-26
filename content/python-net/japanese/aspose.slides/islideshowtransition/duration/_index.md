---
title: duration property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islideshowtransition/duration/
weight: 40
---
## duration プロパティ
Gets or sets the duration of the slide transition effect in milliseconds.
            読み書き可能 **int**.

### 備考

Corresponds to the `p14:dur` attribute of the `p:transition` element in the PresentationML schema.
            If not set, the duration is determined automatically based on the [`ISlideShowTransition.speed`](/slides/python-net/ja/aspose.slides/islideshowtransition/speed) プロパティ
            and the transition type.

### 定義:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 関連項目
* クラス [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)