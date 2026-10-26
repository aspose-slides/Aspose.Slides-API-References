---
title: IndexOf()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ส่งคืนดัชนีของอ็อบเจ็กต์ SummaryZoomSection ที่ระบุ.
type: docs
weight: 66
url: /th/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) เมธอด

คืนค่าอินดексаของอ็อบเจ็กต์ [SummaryZoomSection](../../summaryzoomsection/) ที่ระบุ.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | อ็อบเจ็กต์ [SummaryZoomSection](../../summaryzoomsection/) เพื่อค้นหา [ISummaryZoomSection](../../isummaryzoomsection/). |

### ค่าที่ส่งคืน

ดัชนีของอ็อบเจ็กต์ [SummaryZoomSection](../../summaryzoomsection/) หรือ -1 หากอ็อบเจ็กต์ [SummaryZoomSection](../../summaryzoomsection/) ไม่ได้มาจากคอลเลกชันนี้.

## หมายเหตุ

ตัวอย่างนี้แสดงการดึงองค์ประกอบ Summary Zoom [Section](../../section/) โดยใช้ดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSection](../../isummaryzoomsection/)
* คลาส [SummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)