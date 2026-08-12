---
title: InsertZoomFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งดัชนีที่ระบุ
type: docs
weight: 118
url: /th/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) เมธอด

สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีแบบศูนย์ฐานที่ใช้ในการแทรกเฟรม Zoom. |
| x | **float** | ค่าพิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| y | **float** | ค่าพิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยเฟรม Zoom. |

### ค่าที่ส่งกลับ

[IZoomFrame](../../izoomframe/) ที่สร้างใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการสร้างและแทรกวัตถุ Zoom ที่ตำแหน่งที่ระบุของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) เมธอด

สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีแบบศูนย์ฐานที่ใช้ในการแทรกเฟรม Zoom. |
| x | **float** | ค่าพิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| y | **float** | ค่าพิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นพอยต์. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ที่อ้างอิงโดยเฟรม Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../ippimage/). |

### ค่าที่ส่งกลับ

[IZoomFrame](../../izoomframe/) ที่สร้างใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการสร้างและแทรกวัตถุ Zoom ที่ตำแหน่งที่ระบุของคอลเลกชัน (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)