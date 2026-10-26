---
title: get_SlideSize()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอ็อบเจ็กต์ขนาดสไลด์. อ่านอย่างเดียว ISlideSize.
type: docs
weight: 79
url: /th/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() เมธอด

ส่งคืนอ็อบเจ็กต์ขนาดสไลด์. Read-only [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## หมายเหตุ

The following example shows how to change the slide size in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 The following example shows how to set slide size with respect to content scaling for a PowerPoint [Presentation](../). 
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงถึงไฟล์การพรีเซนเทชัน
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// ตั้งค่าขนาดสไลด์ของการพรีเซนเทชันที่สร้างขึ้นให้เท่ากับของต้นฉบับ
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// เมธอด SetSize ถูกใช้เพื่อกำหนดขนาดสไลด์โดยปรับสเกลเนื้อหาเพื่อให้พอดี
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// เมธอด SetSize ถูกใช้เพื่อกำหนดขนาดสไลด์โดยขยายขนาดเนื้อหาให้เต็มที่
// บันทึก Presentation ลงดิสก์
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to specifying custom slide sizes in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// ขนาดกระดาษ A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlideSize](../../islidesize/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)