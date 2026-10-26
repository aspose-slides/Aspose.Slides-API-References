---
title: get_IsValid()
second_title: Aspose.Slides for C++ API Referansı
description: Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olacaktır. Salt-okunur bool.
type: docs
weight: 14
url: /tr/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() yöntemi

Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olacaktır. Salt-okunur **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Diğer Bağlantılar

* Sınıf [DigitalSignature](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)