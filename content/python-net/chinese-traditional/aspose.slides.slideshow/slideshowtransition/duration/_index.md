---
title: duration property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.slideshow/slideshowtransition/duration/
weight: 40
---
## duration 屬性
取得或設定投影片轉場效果的 duration（以毫秒為單位）。
讀/寫 **int**。

### 備註

對應於 PresentationML 架構中 `p:transition` 元素的 `p14:dur` 屬性。
如果未設定，duration 將根據 [`SlideShowTransition.speed`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition/speed) 屬性和轉場類型自動決定。

### 定義:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 另請參閱
* 類別 [`SlideShowTransition`](/slides/python-net/zh-hant/aspose.slides.slideshow/slideshowtransition)
* 模組 [`aspose.slides.slideshow`](/slides/python-net/zh-hant/aspose.slides.slideshow)
* 函式庫 [`Aspose.Slides`](/slides/python-net)