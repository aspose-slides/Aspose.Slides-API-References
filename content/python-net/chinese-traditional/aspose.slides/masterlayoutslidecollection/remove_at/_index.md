---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
移除集合中指定索引的元素。

```python
def remove_at(self, index):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要移除之元素的零基索引。 |

### 備註

1) 為避免拋出 PptxEditException，請先檢查 layout 的 HasDependingSlides 屬性。  
2) 您也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide/remove) 方法簡化程式碼。

### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果 layout 已在簡報中使用 (其 HasDependingSlides 屬性為 true) 則拋出此例外。 |

### 另請參閱
* 類別 [`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)