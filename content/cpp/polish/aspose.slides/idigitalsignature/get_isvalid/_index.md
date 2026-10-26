---
title: get_IsValid()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Jeśli ten podpis cyfrowy jest ważny i dokument nie został naruszony, ta wartość będzie prawdziwa. Tylko do odczytu bool.
type: docs
weight: 14
url: /pl/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() metoda


Jeśli ten podpis cyfrowy jest ważny i dokument nie został naruszony, ta wartość będzie prawdziwa. Tylko do odczytu **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Zobacz także

* Klasa [IDigitalSignature](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)