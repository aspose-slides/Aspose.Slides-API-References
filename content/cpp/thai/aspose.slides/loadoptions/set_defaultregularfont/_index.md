---
title: set_DefaultRegularFont()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "กำหนดแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน System::String."
type: docs
weight: 40
url: /th/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) เมธอด


ตั้งค่าแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าแบบอักษรเริ่มต้นสำหรับการแสดงผล PowerPoint [Presentation](../../presentation/). 
```cpp
// ใช้ load options เพื่อกำหนดแบบอักษรปกติและแบบอักษรเอเชียนเริ่มต้น
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// โหลดงานนำเสนอ
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// สร้างภาพย่อของสไลด์
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// สร้าง PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// สร้าง XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [LoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)