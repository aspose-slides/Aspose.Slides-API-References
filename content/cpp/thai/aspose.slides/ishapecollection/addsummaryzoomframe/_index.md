---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างกรอบ Summary Zoom ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.
type: docs
weight: 144
url: /th/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) เมธอด

สร้างกรอบ Summary Zoom ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของกรอบ Summary Zoom ใหม่, มีหน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของกรอบ Summary Zoom ใหม่, มีหน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของกรอบ Summary Zoom ใหม่, มีหน่วยเป็นพอยต์. |
| height | **float** | ความสูงของกรอบ Summary Zoom ใหม่, มีหน่วยเป็นพอยต์. |

### ค่าที่คืน

[ISummaryZoomFrame](../../isummaryzoomframe/) ที่สร้างใหม่.

## หมายเหตุ

เมธอดนี้สร้างกรอบ Summary Zoom ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ.  

ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Summary Zoom เข้าไปที่ส่วนท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):  
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomFrame](../../isummaryzoomframe/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)