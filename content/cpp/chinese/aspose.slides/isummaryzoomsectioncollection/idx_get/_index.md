---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定索引处的元素。只读 ISummaryZoomSection。
type: docs
weight: 1
url: /zh/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) 方法

获取指定索引处的元素。只读 [ISummaryZoomSection](../../isummaryzoomsection/)。

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## 备注

示例演示了通过索引获取 Summary Zoom [Section](../../section/) 元素： 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISummaryZoomSection](../../isummaryzoomsection/)
* 类 [ISummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)