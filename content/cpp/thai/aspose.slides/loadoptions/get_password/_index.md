---
title: get_Password()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "รับรหัสผ่าน อ่าน System::String."
type: docs
weight: 105
url: /th/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() เมธอด

รับรหัสผ่าน อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## หมายเหตุ

รหัสผ่าน.

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปิด PowerPoint ที่ป้องกันด้วยรหัสผ่าน [Presentation](../../presentation/).
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