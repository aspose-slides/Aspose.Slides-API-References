---
title: GetSummarySection()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าองค์ประกอบ Summary Zoom Section สำหรับเซกชันที่กำหนด.
type: docs
weight: 27
url: /th/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) method


Returns Summary Zoom [Section](../../section/) element for the given section.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) เพื่อค้นหา [ISection](../../isection/) |

### ค่าที่คืนกลับ

[ISummaryZoomSection](../../isummaryzoomsection/) or null if collection does not contains element for the section.
## หมายเหตุ



The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSection](../../isummaryzoomsection/)
* คลาส [ISection](../../isection/)
* คลาส [ISummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)