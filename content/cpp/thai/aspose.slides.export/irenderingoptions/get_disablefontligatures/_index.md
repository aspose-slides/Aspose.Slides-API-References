---
title: get_DisableFontLigatures()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น true ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งค่าเป็น false.
type: docs
weight: 40
url: /th/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() method


รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิเกเจอร์ เมื่อกำหนดเป็น **true** ลิเกเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งค่าเป็น **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
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

* คลาส [IRenderingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)