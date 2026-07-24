---
title: get_SignTime()
second_title: Aspose.Slides für C++ API-Referenz
description: "Die Zeit, zu der das Dokument signiert wurde. Schreibgeschützt System::DateTime."
type: docs
weight: 27
url: /de/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() Methode


Die Zeit, zu der das Dokument signiert wurde. Schreibgeschützt [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Siehe auch

* Klasse [DateTime](../../../system/datetime/)
* Klasse [IDigitalSignature](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)