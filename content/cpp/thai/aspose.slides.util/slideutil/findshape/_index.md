---
title: FindShape()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ค้นหารูปร่างโดยใช้ข้อความแทนในงานนำเสนอ PPTX.
type: docs
weight: 1
url: /th/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method

ค้นหารูปร่างโดยใช้ข้อความแทนในงานนำเสนอ PPTX

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | งานนำเสนอที่สแกน. |
| altText | [System::String](../../../system/string/) | ข้อความแทนของรูปร่าง. |

### ค่าที่ส่งคืน

[Shape](../../../aspose.slides/shape/) หรือ null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method

ค้นหารูปร่างโดยใช้ข้อความแทนบนสไลด์ในงานนำเสนอ PPTX

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | สไลด์ที่สแกน. |
| altText | [System::String](../../../system/string/) | ข้อความแทนของรูปร่าง. |

### ค่าที่ส่งคืน

[Shape](../../../aspose.slides/shape/) หรือ null.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../../aspose.slides/ishape/)
* คลาส [IPresentation](../../../aspose.slides/ipresentation/)
* คลาส [String](../../../system/string/)
* คลาส [SlideUtil](../)
* คลาส [IBaseSlide](../../../aspose.slides/ibaseslide/)
* เนมสเปซ [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)