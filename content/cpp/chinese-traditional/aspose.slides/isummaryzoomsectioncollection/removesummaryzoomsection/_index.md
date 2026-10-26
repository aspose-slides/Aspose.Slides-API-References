---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除 Summary Zoom Section 物件。
type: docs
weight: 40
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

從集合中移除 Summary Zoom [Section](../../section/) 物件。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/)，其 Summary Zoom [Section](../../section/) 元素將被移除 [ISection](../../isection/)。 |
## 備註

範例說明如何透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [ISummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)