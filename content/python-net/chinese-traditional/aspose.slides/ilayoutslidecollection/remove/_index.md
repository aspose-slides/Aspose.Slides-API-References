---
title: remove method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
從集合中移除佈局。


```python
def remove(self, value):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要從集合中移除的佈局投影片。 |

### 備註

1) 為避免拋出 PptxEditException，請事先檢查佈局的 HasDependingSlides 屬性。
2) 也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide/remove) 方法來簡化程式碼。

### 例外情況

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果佈局在簡報中被使用（其 HasDependingSlides 屬性為 true），則拋出此例外。 |



### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`ILayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/ilayoutslidecollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)