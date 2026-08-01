---
title: get_SignTime()
second_title: Aspose.Slides voor C++ API-referentie
description: "De tijd waarop het document is ondertekend. Alleen-lezen System::DateTime."
type: docs
weight: 27
url: /nl/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() methode


De tijd waarop het document is ondertekend. Alleen-lezen [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Opmerkingen



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

## Zie ook

* Klasse [DateTime](../../../system/datetime/)
* Klasse [DigitalSignature](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)