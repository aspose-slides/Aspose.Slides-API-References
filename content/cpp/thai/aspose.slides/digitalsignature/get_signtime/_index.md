---
title: get_SignTime()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "เวลาที่เอกสารถูกลงนาม. อ่านอย่างเดียว System::DateTime."
type: docs
weight: 27
url: /th/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() เมธอด


เวลาที่เอกสารถูกลงนาม. อ่านอย่างเดียว [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## ดูเพิ่มเติม

* คลาส [DateTime](../../../system/datetime/)
* คลาส [DigitalSignature](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)