---
title: get_Slides()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว ISlideCollection.
type: docs
weight: 53
url: /th/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() เมธอด


ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีการตั้งค่าสีพื้นหลังของสไลด์ใน PowerPoint [Presentation](../). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// ตั้งค่าสีพื้นหลังของ ISlide แรกเป็นสีฟ้า
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการตั้งรูปภาพพื้นหลังของสไลด์ใน PowerPoint [Presentation](../). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// ตั้งค่าพื้นหลังด้วยภาพ
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// ตั้งค่าภาพ
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// เพิ่มภาพลงในคอลเลกชันภาพของงานนำเสนอ
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// บันทึกงานนำเสนอลงดิสก์
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มการเปลี่ยนสไลด์ [Presentation](../). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์งานนำเสนอต้นฉบับ
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// ใช้การเปลี่ยนภาพแบบวงกลมบนสไลด์ที่ 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// ใช้การเปลี่ยนภาพแบบคอมบบนสไลด์ที่ 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// บันทึกงานนำเสนอลงดิสก์
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่ม slide Transition ขั้นสูง. 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// ใช้การเปลี่ยนภาพแบบวงกลมบนสไลด์ที่ 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// ตั้งค่าระยะเวลาเปลี่ยนภาพเป็น 3 วินาที
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// ใช้การเปลี่ยนภาพแบบคอมบบนสไลด์ที่ 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// ตั้งค่าระยะเวลาเปลี่ยนภาพเป็น 5 วินาที
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// ใช้การเปลี่ยนภาพแบบซูมบนสไลด์ที่ 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// ตั้งค่าระยะเวลาเปลี่ยนภาพเป็น 7 วินาที
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// บันทึกงานนำเสนอลงดิสก์
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlideCollection](../../islidecollection/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)