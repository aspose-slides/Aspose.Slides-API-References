---
title: get_DisableFontLigatures()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่มีการใช้ลีเกเจอร์ เมื่อกำหนดเป็น true จะปิดการใช้งานลีเกเจอร์ในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น false.
type: docs
weight: 40
url: /th/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() method


รับค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ได้ใช้ลีเกเจอร์ เมื่อกำหนดเป็น **true** จะปิดการใช้งานลีเกเจอร์ในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ถูกตั้งค่าเป็น **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // ปิดการใช้ลีเกเจอร์ในการแสดงข้อความ

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