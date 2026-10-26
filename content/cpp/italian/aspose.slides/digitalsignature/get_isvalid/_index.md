---
title: get_IsValid()
second_title: Riferimento API di Aspose.Slides per C++
description: Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà vero. Solo lettura bool.
type: docs
weight: 14
url: /it/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() metodo


Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà vero. Solo lettura **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Vedi anche

* Classe [DigitalSignature](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)