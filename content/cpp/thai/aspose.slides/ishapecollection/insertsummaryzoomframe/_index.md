---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างกรอบ Summary Zoom ใหม่และแทรกเข้าไปในคอลเลกชันของรูปทรงที่ตำแหน่งที่ระบุ
type: docs
weight: 157
url: /th/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) เมธอด

สร้างกรอบ Summary Zoom ใหม่แล้วแทรกเข้าไปในคอลเลกชันของรูปทรงที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีแบบศูนย์ฐานที่ใช้แทรกกรอบ Summary Zoom |
| x | **float** | พิกัด x ของกรอบ Summary Zoom ใหม่ หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของกรอบ Summary Zoom ใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของกรอบ Summary Zoom ใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของกรอบ Summary Zoom ใหม่ หน่วยเป็นพอยต์ |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ที่สร้างขึ้นใหม่ [ISummaryZoomFrame](../../isummaryzoomframe/).

## หมายเหตุ

เมธอดนี้สร้างกรอบ Summary Zoom ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ  

ตัวอย่างนี้แสดงการสร้างและแทรกอ็อบเจ็กต์ Summary Zoom ที่ดัชนีที่ระบุของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomFrame](../../isummaryzoomframe/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)