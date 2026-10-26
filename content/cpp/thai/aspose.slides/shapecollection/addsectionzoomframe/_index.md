---
title: AddSectionZoomFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้าง Section Zoom frame ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape
type: docs
weight: 131
url: /th/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method


สร้าง [Section](../../section/) Zoom frame ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างอิงโดย [Section](../../section/) Zoom frame; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างใหม่
## Remarks


ตัวอย่างนี้แสดงการเพิ่มวัตถุ Zoom [Section](../../section/) ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสอง section ในงานนำเสนอ "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


สร้าง [Section](../../section/) Zoom frame ใหม่พร้อมรูปภาพกำหนดล่วงหน้าและเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของ [Section](../../section/) Zoom frame ใหม่, หน่วยเป็นพอยต์ |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ที่อ้างอิงโดย [Section](../../section/) Zoom frame; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) ที่จะแสดงใน [Section](../../section/) Zoom frame |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) ที่สร้างใหม่
## Remarks


ตัวอย่างนี้แสดงการเพิ่มวัตถุ Zoom [Section](../../section/) ไปยังส่วนท้ายของคอลเลกชัน (สมมติว่ามีอย่างน้อยสอง section ในงานนำเสนอ "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISectionZoomFrame](../../isectionzoomframe/)
* คลาส [ISection](../../isection/)
* คลาส [ShapeCollection](../)
* คลาส [IPPImage](../../ippimage/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)