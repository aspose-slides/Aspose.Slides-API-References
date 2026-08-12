---
title: set_DisableFontLigatures()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงผลโดยไม่ใช้ลิการเจอร์. เมื่อกำหนดเป็น **true**, ลิการเจอร์จะถูกปิดการใช้งานในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้น, คุณสมบัตินี้ตั้งค่าเป็น **false**.
type: docs
weight: 53
url: /th/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) เมธอด


กำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงผลโดยไม่ใช้ลิการเจอร์. เมื่อกำหนดเป็น **true**, ลิการเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้น, คุณสมบัตินี้ตั้งค่าเป็น **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // ปิดลิการเจอร์ในการเรนเดอร์ข้อความ

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## ดูเพิ่มเติม

* คลาส [IRenderingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)