---
title: AddZoomFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างกรอบ Zoom ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.
type: docs
weight: 105
url: /th/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) เมธอด

สร้างกรอบ Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | ค่าพิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| y | **float** | ค่าพิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom; ต้องเป็นของงานนำเสนอนี้ |

### ค่าที่ส่งคืน

อ็อบเจกต์ที่สร้างใหม่ [IZoomFrame](../../izoomframe/).

## หมายเหตุ

ตัวอย่างนี้สาธิตการเพิ่มอ็อบเจกต์ Zoom ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) เมธอด

สร้างกรอบ Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | ค่าพิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| y | **float** | ค่าพิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom; ต้องเป็นของงานนำเสนอนี้ |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../ippimage/) |

### ค่าที่ส่งคืน

อ็อบเจกต์ที่สร้างใหม่ [IZoomFrame](../../izoomframe/).

## หมายเหตุ

ตัวอย่างนี้สาธิตการเพิ่มอ็อบเจ็กต์ Zoom ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IZoomFrame](../../izoomframe/)
* คลาส [ISlide](../../islide/)
* คลาส [ShapeCollection](../)
* คลาส [IPPImage](../../ippimage/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)