---
title: IndexOf()
second_title: Aspose.Slides for C++ อ้างอิง API
description: ส่งคืนดัชนีของอ็อบเจกต์ SummaryZoomSection ที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) method

ส่งคืนดัชนีของอ็อบเจกต์ [SummaryZoomSection](../../summaryzoomsection/) ที่ระบุ

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) อ็อบเจกต์เพื่อค้นหา [ISummaryZoomSection](../../isummaryzoomsection/). |

### Return Value

ดัชนีของอ็อบเจกต์ [SummaryZoomSection](../../summaryzoomsection/) หรือ -1 หากอ็อบเจกต์ [SummaryZoomSection](../../summaryzoomsection/) ไม่ได้มาจากคอลเลกชันนี้

## หมายเหตุ



ตัวอย่างแสดงการดึงเอาองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
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
* คลาส [ISummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)