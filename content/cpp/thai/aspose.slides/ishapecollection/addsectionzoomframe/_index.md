---
title: AddSectionZoomFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างกรอบ Section Zoom ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 118
url: /th/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) วิธี

สร้างกรอบซูม [Section](../../section/) ใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | **float** | พิกัด x ของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| y | **float** | พิกัด y ของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างถึงโดยกรอบซูม [Section](../../section/); ต้องเป็นของงานนำเสนอ นี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

### ค่าที่ส่งกลับ

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างขึ้นใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ซูม [Section](../../section/) ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองส่วนในงานนำเสนอ \"Presentation.pptx\"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) วิธี

สร้างกรอบซูม [Section](../../section/) ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | **float** | พิกัด x ของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| y | **float** | พิกัด y ของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของ [Section](../../section/) กรอบซูมใหม่, หน่วยเป็นพ้อยท์ |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างถึงโดยกรอบซูม [Section](../../section/); ต้องเป็นของงานนำเสนอ นี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงภายในกรอบซูม [Section](../../section/) |

### ค่าที่ส่งกลับ

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างขึ้นใหม่

## หมายเหตุ

ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ซูม [Section](../../section/) ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสองส่วนในงานนำเสนอ \"Presentation.pptx\"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISectionZoomFrame](../../isectionzoomframe/)
* คลาส [ISection](../../isection/)
* คลาส [IShapeCollection](../)
* คลาส [IPPImage](../../ippimage/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)