---
title: RemoveAt()
second_title: Aspose.Slides C++ API 参考
description: 从集合中删除指定索引处的元素。
type: docs
weight: 53
url: /zh/aspose.slides/imasterlayoutslidecollection/removeat/
---
## IMasterLayoutSlideCollection::RemoveAt(int32_t) 方法


从集合中删除指定索引处的元素。

```cpp
virtual void Aspose::Slides::IMasterLayoutSlideCollection::RemoveAt(int32_t index)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要删除的元素的零基索引。 |
## 备注



1) 为避免抛出 PptxEditException，请先检查布局的 HasDependingSlides 属性。 2) 也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法来简化代码。 
## 另见

* 类 [IMasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)