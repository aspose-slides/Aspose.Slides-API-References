---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API 参考
description: 获取 Summary Zoom Frame 对象的 ISummaryZoomSectionCollection。
type: docs
weight: 14
url: /zh/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() 方法

获取 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) 供 Summary Zoom Frame 对象使用。

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## 备注

示例演示了获取 Summary Zoom [Section](../../section/) 元素按索引：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)