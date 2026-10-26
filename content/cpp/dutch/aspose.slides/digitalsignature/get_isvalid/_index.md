---
title: get_IsValid()
second_title: Aspose.Slides voor C++ API-referentie
description: Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn. Alleen-lezen bool.
type: docs
weight: 14
url: /nl/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() methode


Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn. Alleen-lezen **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Zie ook

* Klasse [DigitalSignature](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)