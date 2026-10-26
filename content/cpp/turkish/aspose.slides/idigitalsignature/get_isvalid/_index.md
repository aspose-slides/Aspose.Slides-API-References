---
title: get_IsValid()
second_title: Aspose.Slides for C++ API Referansı
description: Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olur. Salt okunur bool.
type: docs
weight: 14
url: /tr/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() yöntemi


Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer **true** olur. Salt okunur **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
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

## Ayrıca Bakınız

* Sınıf [IDigitalSignature](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)