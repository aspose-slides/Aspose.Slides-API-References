---
title: get_SignTime()
second_title: Aspose.Slides voor C++ API-referentie
description: "De tijd waarop het document is ondertekend. Alleen-lezen System::DateTime."
type: docs
weight: 27
url: /nl/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() methode

De tijd waarop het document is ondertekend. Alleen-lezen [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Zie ook

* Klasse [DateTime](../../../system/datetime/)
* Klasse [IDigitalSignature](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)