---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
判斷兩個 IBaseSlide 實例是否相等。
            返回值根據投影片的結構和靜態內容計算。
            兩張投影片相等，當且僅當所有形狀、樣式、文字、動畫及其他設定等全部相等。比較時不會考慮唯一識別碼的值，例如 SlideId，亦不會考慮動態內容，例如日期佔位元中的當前日期值。

### 返回

如果指定的 IBaseSlide 與目前的 IBaseSlide 相等，則為 **true**；否則為 **false** 。

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 要與目前的 IBaseSlide 比較的 IBaseSlide。 |

### 另請參閱
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`NotesSlide`](/slides/python-net/zh-hant/aspose.slides/notesslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)