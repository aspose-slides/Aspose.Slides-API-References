---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考
description: 移除集合中指定索引的元素。
type: docs
weight: 53
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/removeat/
---
## IMasterLayoutSlideCollection::RemoveAt(int32_t) method


移除集合中指定索引的元素。

```cpp
virtual void Aspose::Slides::IMasterLayoutSlideCollection::RemoveAt(int32_t index)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除的元素的零基索引。 |
## 備註

1) 為避免拋出 PptxEditException，請先檢查 layout 的 HasDependingSlides 屬性。 2) 您也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法簡化程式碼。 
## 另請參閱

* 類別 [IMasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)