---
title: get_IsValid()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่าตัวนี้จะเป็นจริง. อ่านอย่างเดียว bool.
type: docs
weight: 14
url: /th/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() เมธอด

หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่มีการดัดแปลง ค่าตัวนี้จะเป็นจริง. อ่านอย่างเดียว **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## ดูเพิ่มเติม

* คลาส [DigitalSignature](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)