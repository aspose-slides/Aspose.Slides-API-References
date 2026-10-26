---
title: get_SignTime()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Czas, w którym dokument został podpisany. Tylko do odczytu System::DateTime."
type: docs
weight: 27
url: /pl/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() metoda


Czas, w którym dokument został podpisany. Tylko do odczytu [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Uwagi



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

## Zobacz także

* Klasa [DateTime](../../../system/datetime/)
* Klasa [DigitalSignature](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)