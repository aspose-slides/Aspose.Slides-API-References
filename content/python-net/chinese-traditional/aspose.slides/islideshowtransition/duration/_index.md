---
title: duration property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islideshowtransition/duration/
weight: 40
---
## duration 屬性
取得或設定 duration（以毫秒為單位），用於投影片轉場效果。
            讀/寫 **int**.

### 備註

對應於 PresentationML 架構中 `p:transition` 元素的 `p14:dur` 屬性。
            如果未設定，duration 會根據 [`ISlideShowTransition.speed`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition/speed) 屬性和過渡類型自動決定。

### 定義:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 另見
* 類別 [`ISlideShowTransition`](/slides/python-net/zh-hant/aspose.slides/islideshowtransition)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)