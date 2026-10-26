---
title: Clear()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中移除所有 SummaryZoomSection 对象。
type: docs
weight: 66
url: /zh/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() 方法

从集合中移除所有 [SummaryZoomSection](../../summaryzoomsection/) 对象。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## 备注

示例演示通过索引获取 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 另请参见

* 类 [ISummaryZoomSectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)