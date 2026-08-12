---
title: InsertZoomFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างกรอบ Zoom ใหม่และแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่ระบุ.
type: docs
weight: 105
url: /th/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) เมธอด

สร้างกรอบ Zoom ใหม่และแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### อาร์กิวเมนต์

| พารามิ터 | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้แทรกกรอบ Zoom. |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom. |

### ค่าที่ส่งกลับ

[IZoomFrame](../../izoomframe/) ที่สร้างขึ้นใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการสร้างและการแทรกวัตถุ Zoom ที่ตำแหน่งที่ระบุของคอลเลกชัน (ถือว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) เมธอด

สร้างกรอบ Zoom ใหม่พร้อมรูปภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปแบบที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้แทรกกรอบ Zoom. |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบ Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยกรอบ Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../ippimage/). |

### ค่าที่ส่งกลับ

[IZoomFrame](../../izoomframe/) ที่สร้างขึ้นใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการสร้างและการแทรกวัตถุ Zoom ที่ตำแหน่งที่ระบุของคอลเลกชัน (ถือว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IZoomFrame](../../izoomframe/)
* คลาส [ISlide](../../islide/)
* คลาส [IShapeCollection](../)
* คลาส [IPPImage](../../ippimage/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)