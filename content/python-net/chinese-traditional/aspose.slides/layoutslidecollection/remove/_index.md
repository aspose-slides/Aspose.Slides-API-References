---
title: remove method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
從集合中移除版面配置。

```python
def remove(self, value):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要從集合中移除的版面投影片。 |

### 備註

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。  
2) 您也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide/remove) 方法來簡化程式碼。

### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果版面在簡報中被使用（其 HasDependingSlides 屬性為 true），則拋出此例外。 |

### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`LayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)