---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
判斷兩個IBaseSlide實例是否相等。
計算返回值時會根據投影片的結構和靜態內容。
如果所有形狀、樣式、文字、動畫以及其他設定等均相同，則兩張投影片相等。比較時不會考慮唯一識別碼的值，例如SlideId，以及動態內容，例如日期佔位符中的當前日期值。

### 回傳值

**true** 如果指定的IBaseSlide等於目前的IBaseSlide；否則，**false** 。

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 用於與目前的IBaseSlide比較的IBaseSlide。 |

### 另請參閱
* 類別 [`BaseSlide`](/slides/python-net/zh-hant/aspose.slides/baseslide)
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)