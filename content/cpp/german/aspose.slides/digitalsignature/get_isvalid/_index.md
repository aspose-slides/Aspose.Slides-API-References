---
title: get_IsValid()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert wahr. Nur lesbar bool.
type: docs
weight: 14
url: /de/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() Methode


Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert wahr. Nur lesbar **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Hinweise



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Siehe auch

* Klasse [DigitalSignature](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)