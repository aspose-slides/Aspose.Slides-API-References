---
title: get_IsValid()
second_title: Aspose.Slides pro C++ API Reference
description: Pokud je tento digitální podpis platný a dokument nebyl pozměněn, bude tato hodnota true. Pouze ke čtení bool.
type: docs
weight: 14
url: /cs/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() metoda


Pokud je tento digitální podpis platný a dokument nebyl poškozen, bude tato hodnota true. Pouze ke čtení **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Viz také

* Třída [IDigitalSignature](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)