---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 Summary Zoom Frame 物件的 ISummaryZoomSectionCollection。
type: docs
weight: 14
url: /zh-hant/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() 方法

取得 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) 針對 Summary Zoom Frame 物件。

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## 備註

範例示範如何依索引取得 Summary Zoom [Section](../../section/) 元素：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)