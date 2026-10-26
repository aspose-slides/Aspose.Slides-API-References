---
title: InsertSectionZoomFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้าง Section Zoom frame ใหม่และแทรกลงใน shape collection ที่ตำแหน่งดัชนีที่ระบุ.
type: docs
weight: 144
url: /th/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) เมธอด

สร้าง [Section](../../section/) Zoom frame ใหม่และแทรกเข้าไปใน shape collection ที่ตำแหน่งดัชนีที่ระบุ

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจาก 0 ที่จะใช้ในการแทรก [Section](../../section/) Zoom frame |
| x | **float** | พิกัด x ของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างอิงโดย [Section](../../section/) Zoom frame; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างขึ้นใหม่

## Remarks

ตัวอย่างนี้สาธิตการสร้างและแทรก [Section](../../section/) Zoom object ที่ตำแหน่งดัชนีที่ระบุของคอลเล็กชัน (สมมติว่ามีอย่างน้อยสอง section ในงานนำเสนอ “Presentation.pptx”):  
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) เมธอด

สร้าง [Section](../../section/) Zoom frame ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าไปใน shape collection ที่ตำแหน่งดัชนีที่ระบุ

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจาก 0 ที่จะใช้ในการแทรก [Section](../../section/) Zoom frame |
| x | **float** | พิกัด x ของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของ [Section](../../section/) Zoom frame ใหม่ หน่วยเป็น point |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างอิงโดย [Section](../../section/) Zoom frame; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | รูปภาพที่จะแสดงภายใน [Section](../../section/) Zoom frame |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างขึ้นใหม่

## Remarks

ตัวอย่างนี้สาธิตการสร้างและแทรก [Section](../../section/) Zoom object ที่ตำแหน่งดัชนีที่ระบุของคอลเล็กชัน (สมมติว่ามีอย่างน้อยสอง section ในงานนำเสนอ “Presentation.pptx”):  
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISectionZoomFrame](../../isectionzoomframe/)
* คลาส [ISection](../../isection/)
* คลาส [ShapeCollection](../)
* คลาส [IPPImage](../../ippimage/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)