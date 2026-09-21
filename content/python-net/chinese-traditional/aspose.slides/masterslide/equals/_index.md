---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
判斷兩個 IBaseSlide 實例是否相等。
            返回值根據投影片的結構和靜態內容計算。
            如果所有形狀、樣式、文字、動畫以及其他設定等全部相等，則兩個投影片相同。比較不會考慮唯一識別碼值，例如 SlideId，及動態內容，例如日期佔位符中的當前日期值。

### 返回值

**true**  if the specified IBaseSlide is equal to the current IBaseSlide; 
            otherwise, **false** .

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 用於與當前 IBaseSlide 比較的 IBaseSlide。 |

### 另請參閱
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`MasterSlide`](/slides/python-net/zh-hant/aspose.slides/masterslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)