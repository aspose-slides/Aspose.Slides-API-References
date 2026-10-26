---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าค่าที่ระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น false.
type: docs
weight: 53
url: /th/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) เมธอด


ตั้งค่าค่าซึ่งระบุว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น **true** ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลิเกเจอร์ในการเรนเดอร์ข้อความ

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## ดูเพิ่มเติม

* คลาส [RenderingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)