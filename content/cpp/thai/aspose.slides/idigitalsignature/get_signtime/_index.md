---
title: get_SignTime()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "เวลาที่เอกสารถูกเซ็น. อ่านอย่างเดียว System::DateTime."
type: docs
weight: 27
url: /th/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() method

เวลาที่เอกสารถูกเซ็น. อ่านอย่างเดียว [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## ดูเพิ่มเติม

* คลาส [DateTime](../../../system/datetime/)
* คลาส [IDigitalSignature](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)