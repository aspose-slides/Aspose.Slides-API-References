---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
判斷兩個IBaseSlide實例是否相等。
返回值是根據投影片的結構和靜態內容計算的。
若所有形狀、樣式、文字、動畫及其他設定等都相同，則兩個投影片相等。比較不會考慮唯一識別碼值，例如SlideId，以及動態內容，例如日期占位符中的當前日期值。

### 返回值

**true**  if the specified IBaseSlide is equal to the current IBaseSlide; 
            otherwise, **false** .

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 要與目前的IBaseSlide比較的IBaseSlide。 |

### 另請參閱
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`MasterHandoutSlide`](/slides/python-net/zh-hant/aspose.slides/masterhandoutslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)