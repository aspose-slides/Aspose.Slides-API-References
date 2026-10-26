---
title: RemoveAt()
second_title: Aspose.Slides C++ API 参考
description: 删除集合中指定索引处的元素。
type: docs
weight: 53
url: /zh/aspose.slides/masterlayoutslidecollection/removeat/
---
## MasterLayoutSlideCollection::RemoveAt(int32_t) 方法

删除集合中指定索引处的元素。

```cpp
void Aspose::Slides::MasterLayoutSlideCollection::RemoveAt(int32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要删除的元素的零基索引。 |
## 备注

1) 为避免抛出 PptxEditException，请在之前检查布局的 HasDependingSlides 属性。2) 也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法来简化代码。 
## 另请参阅

* 类 [MasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)