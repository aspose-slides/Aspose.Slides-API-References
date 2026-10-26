---
title: equals method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
判斷兩個 IBaseSlide 實例是否相等。
返回值是根據投影片的結構和靜態內容計算的。
如果所有形狀、樣式、文字、動畫以及其他設定等都相等，則兩張投影片相等。比較時不會考慮唯一識別碼值，例如 SlideId，亦不會考慮動態內容，例如日期佔位符中的當前日期值。

### 傳回值

**true**  如果指定的 IBaseSlide 與目前的 IBaseSlide 相等； 
            否則為 **false** .

```python
def equals(self, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 用於與目前的 IBaseSlide 進行比較的 IBaseSlide。 |

### 另請參閱
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)