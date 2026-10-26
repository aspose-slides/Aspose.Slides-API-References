---
title: get_MasterTheme()
second_title: Aspose.Slides สำหรับ API ของ C++
description: "ส่งคืนธีมหลัก. อ่านอย่างเดียว Theme::IMasterTheme."
type: docs
weight: 404
url: /th/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() เมธอด


ส่งคืนธีมหลัก. อ่านอย่างเดียว [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนผลของธีมโดยการแก้ไขส่วนต่าง ๆ ขององค์ประกอบใน PowerPoint [Presentation](../). 
```cpp
// สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)