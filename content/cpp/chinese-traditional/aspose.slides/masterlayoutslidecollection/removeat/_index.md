---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考文件
description: 移除集合中位於指定索引的元素。
type: docs
weight: 53
url: /zh-hant/aspose.slides/masterlayoutslidecollection/removeat/
---
## MasterLayoutSlideCollection::RemoveAt(int32_t) 方法

移除集合中位於指定索引的元素。

```cpp
void Aspose::Slides::MasterLayoutSlideCollection::RemoveAt(int32_t index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除的元素之零基索引。 |
## 備註

1) 為避免拋出 PptxEditException，請先檢查 layout 的 HasDependingSlides 屬性。2) 亦可使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法來簡化程式碼。 
## 參見

* 類別 [MasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)