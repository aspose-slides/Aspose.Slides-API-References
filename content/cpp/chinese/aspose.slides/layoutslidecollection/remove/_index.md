---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中移除布局。
type: docs
weight: 66
url: /zh/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) 方法

从集合中移除布局。

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 要从集合中移除的布局幻灯片。 |
## 备注

1) 为避免抛出 PptxEditException，请先检查布局的 HasDependingSlides 属性。2) 您也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法来简化代码。 
## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [LayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)