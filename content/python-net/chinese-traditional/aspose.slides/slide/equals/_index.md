---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
判斷兩個 IBaseSlide 實例是否相等。
            回傳值是根據投影片的結構和靜態內容計算的。
            當所有形狀、樣式、文字、動畫以及其他設定等全部相等時，兩個投影片即視為相等。比較不會考慮唯一標識符值，例如 SlideId，亦不會考慮動態內容，例如日期佔位符中的目前日期值。

### Returns

**true** 如果指定的 IBaseSlide 與目前的 IBaseSlide 相等； 
            否則，**false** 。

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 要與目前的 IBaseSlide 進行比較的 IBaseSlide。 |

### 另請參閱
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)