---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้าง Summary Zoom frame ใหม่และแทรกลงในคอลเลกชันของ shape ที่ดัชนีที่ระบุ
type: docs
weight: 170
url: /th/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) เมธอด

สร้าง Summary Zoom frame ใหม่และแทรกลงใน shape collection ที่ดัชนีที่ระบุ

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรก Summary Zoom frame |
| x | **float** | พิกัด x ของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Summary Zoom frame ใหม่, หน่วยเป็นจุด |

### Return Value

[ISummaryZoomFrame](../../isummaryzoomframe/) ที่สร้างขึ้นใหม่

## หมายเหตุ

เมธอดนี้สร้าง Summary Zoom frame ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ

ตัวอย่างนี้แสดงการสร้างและแทรกวัตถุ Summary Zoom ที่ดัชนีที่ระบุของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomFrame](../../isummaryzoomframe/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)