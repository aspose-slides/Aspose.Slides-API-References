---
title: get_Masters()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนรายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดไว้ในงานนำเสนอ. อ่านอย่างเดียว IMasterSlideCollection.
type: docs
weight: 118
url: /th/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() เมธอด

ส่งคืนรายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดไว้ในงานนำเสนอ. อ่านอย่างเดียว [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่ม [Images](../../images/) ไปยังมาสเตอร์ [Slides](../../) ของ PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนสีพื้นหลังของสไลด์มาสเตอร์ของ PowerPoint [Presentation](../). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>();

// ตั้งค่าสีพื้นหลังของ Master ISlide เป็นสีเขียวป่า
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// เขียนงานนำเสนอลงดิสก์
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มเลย์เอาต์สไลด์ให้กับ PowerPoint [Presentation](../). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์งานนำเสนอ
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// ลองค้นหาโดยประเภทสไลด์เลย์เอาต์
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // สถานการณ์ที่งานนำเสนอไม่มีบางประเภทของเลย์เอาต์
    // ไฟล์งานนำเสนอมีเพียงประเภทเลย์เอาต์ Blank และ Custom
    // แต่สไลด์เลย์เอาต์ที่เป็นประเภท Custom มีชื่อสไลด์ที่แตกต่างกัน,
    // เช่น "Title", "Title and Content", เป็นต้น และเป็นไปได้ที่จะใช้ชื่อเหล่านี้
    // เพื่อการเลือกสไลด์เลย์เอาต์
    // นอกจากนี้ยังสามารถใช้ชุดประเภทของรูปร่าง placeholder ได้ ตัวอย่างเช่น,
    // สไลด์ Title ควรมีเฉพาะประเภท placeholder Title เท่านั้น, เป็นต้น.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// เพิ่มสไลด์เปล่าด้วยเลย์เอาต์สไลด์ที่เพิ่มเข้ามา
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// บันทึกงานนำเสนอ
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)