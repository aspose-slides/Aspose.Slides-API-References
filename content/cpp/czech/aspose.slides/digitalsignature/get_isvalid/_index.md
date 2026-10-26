---
title: get_IsValid()
second_title: Aspose.Slides pro C++ API Reference
description: Pokud je tento digitální podpis platný a dokument nebyl pozměněn, bude tato hodnota true. Pouze pro čtení bool.
type: docs
weight: 14
url: /cs/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() metoda


Pokud je tento digitální podpis platný a dokument nebyl pozměněn, tato hodnota bude true. Pouze pro čtení **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

* Třída [DigitalSignature](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)