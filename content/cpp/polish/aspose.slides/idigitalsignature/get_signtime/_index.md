---
title: get_SignTime()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Czas, w którym dokument został podpisany. Tylko do odczytu System::DateTime."
type: docs
weight: 27
url: /pl/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() metoda


Czas, w którym dokument został podpisany. Tylko do odczytu [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Zobacz także

* Klasa [DateTime](../../../system/datetime/)
* Klasa [IDigitalSignature](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)