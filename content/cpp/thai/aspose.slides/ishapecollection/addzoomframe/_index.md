---
title: AddZoomFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างกรอบ Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape.
type: docs
weight: 92
url: /th/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) เมธอด

สร้างกรอบ Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom; ต้องเป็นของงานนำเสนอนี้ |

### ค่าที่คืน

[IZoomFrame](../../izoomframe/) ที่สร้างใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Zoom ลงในส่วนท้ายของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) เมธอด

สร้างกรอบ Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom; ต้องเป็นของงานนำเสนอนี้ |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../ippimage/) |

### ค่าที่คืน

[IZoomFrame](../../izoomframe/) ที่สร้างใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Zoom ลงในส่วนท้ายของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)