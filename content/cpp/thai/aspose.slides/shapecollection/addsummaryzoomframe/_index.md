---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างกรอบ Summary Zoom ใหม่และเพิ่มลงในจุดสิ้นสุดของคอลเลกชันรูปร่าง
type: docs
weight: 157
url: /th/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) เมธอด

สร้าง Summary Zoom frame ใหม่และเพิ่มมันไปยังจุดสิ้นสุดของคอลเลกชันรูปร่าง

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |

### Return Value

อ็อบเจ็กต์ที่สร้างใหม่ [ISummaryZoomFrame](../../isummaryzoomframe/).

## Remarks

เมธอดนี้สร้าง Summary Zoom ใหม่และใส่คอลเลกชันของอ็อบเจ็กต์ลงไปสำหรับทุกเซกชันในงานนำเสนอนี้  

ตัวอย่างนี้แสดงการเพิ่มอ็อบเจ็กต์ Summary Zoom ไปยังจุดท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองเซกชันในงานนำเสนอ "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomFrame](../../isummaryzoomframe/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)