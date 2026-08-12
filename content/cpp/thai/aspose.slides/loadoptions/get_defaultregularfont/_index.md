---
title: get_DefaultRegularFont()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "คืนค่าแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง. อ่าน System::String."
type: docs
weight: 27
url: /th/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() เมธอด

คืนค่าแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง. อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าแบบอักษรเริ่มต้นสำหรับการเรนเดอร์ PowerPoint [Presentation](../../presentation/).

```cpp
// ใช้ตัวเลือกการโหลดเพื่อกำหนดแบบอักษรปกติและเอเชียเริ่มต้น
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// โหลดการนำเสนอ
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// สร้างภาพย่อสไลด์
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