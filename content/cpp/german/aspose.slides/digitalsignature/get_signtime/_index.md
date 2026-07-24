---
title: get_SignTime()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Zeitpunkt, zu dem das Dokument signiert wurde. Nur lesbar System::DateTime."
type: docs
weight: 27
url: /de/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() Methode


Der Zeitpunkt, zu dem das Dokument signiert wurde. Nur lesbar [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Hinweise



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

## Siehe auch

* Klasse [DateTime](../../../system/datetime/)
* Klasse [DigitalSignature](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)