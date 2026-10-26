---
title: set_Password()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตั้งค่ารหัสผ่าน เขียน System::String."
type: docs
weight: 118
url: /th/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) เมธอด

ตั้งค่ารหัสผ่าน เขียน [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## หมายเหตุ

รหัสผ่าน.

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการเปิดไฟล์ PowerPoint ที่ป้องกันด้วยรหัสผ่าน [Presentation](../../presentation/).
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [LoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)