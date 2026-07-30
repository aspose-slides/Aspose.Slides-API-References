---
title: get_SignTime()
second_title: Riferimento API Aspose.Slides per C++
description: "Il momento in cui il documento è stato firmato. Solo lettura System::DateTime."
type: docs
weight: 27
url: /it/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() metodo


Il momento in cui il documento è stato firmato. Solo lettura [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Vedi anche

* Classe [DateTime](../../../system/datetime/)
* Classe [IDigitalSignature](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)