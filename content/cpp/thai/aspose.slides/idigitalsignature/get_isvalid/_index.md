---
title: get_IsValid()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: หากลายเซ็นดิจิทัลนี้เป็นที่ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่าดังกล่าวจะเป็น true. อ่านอย่างเดียว bool.
type: docs
weight: 14
url: /th/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() เมธอด


หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่าดังกล่าวจะเป็น true. อ่านอย่างเดียว **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
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

* คลาส [IDigitalSignature](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)