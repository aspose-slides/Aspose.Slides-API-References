---
title: get_IsValid()
second_title: Riferimento API di Aspose.Slides per C++
description: Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true. Solo lettura bool.
type: docs
weight: 14
url: /it/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() metodo


Se questa firma digitale è valida e il documento non è stato manomesso, questo valore sarà true. Solo lettura **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
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

* Classe [IDigitalSignature](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)