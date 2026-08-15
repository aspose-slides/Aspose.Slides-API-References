---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 Summary Zoom Frame 物件的 ISummaryZoomSectionCollection。
type: docs
weight: 14
url: /zh-hant/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() 方法


取得 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) 供 Summary Zoom Frame 物件使用。

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## 備註


此範例示範依索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* 類別 [ISummaryZoomFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)