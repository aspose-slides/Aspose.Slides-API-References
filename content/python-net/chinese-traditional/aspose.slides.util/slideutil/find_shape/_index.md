---
title: find_shape method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
在 PPTX 簡報中依替代文字尋找形狀。

### 回傳值

Shape 或 None。



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) | 已掃描的簡報。 |
| alt_text | **str** | 形狀的替代文字。 |


## find_shape(slide, alt_text) {#ibaseslide-str}
在 PPTX 簡報的投影片中依替代文字尋找形狀。

### 回傳值

Shape 或 None。



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 已掃描的投影片。 |
| alt_text | **str** | 形狀的替代文字。 |



### 另見
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 類別 [`SlideUtil`](/slides/python-net/zh-hant/aspose.slides.util/slideutil)
* 模組 [`aspose.slides.util`](/slides/python-net/zh-hant/aspose.slides.util)
* 函式庫 [`Aspose.Slides`](/slides/python-net)