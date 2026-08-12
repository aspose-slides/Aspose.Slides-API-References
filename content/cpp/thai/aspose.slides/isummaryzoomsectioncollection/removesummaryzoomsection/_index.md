---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ลบออบเจกต์ Summary Zoom Section ออกจากคอลเลกชัน
type: docs
weight: 40
url: /th/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) เมธอด

Remove Summary Zoom [Section](../../section/) object from the collection.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) ที่องค์ประกอบ Summary Zoom [Section](../../section/) จะถูกลบ [ISection](../../isection/). |

## หมายเหตุ

The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)