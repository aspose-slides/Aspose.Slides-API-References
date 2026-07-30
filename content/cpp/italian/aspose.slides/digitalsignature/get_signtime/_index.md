---
title: get_SignTime()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tempo in cui il documento è stato firmato. Solo lettura System::DateTime."
type: docs
weight: 27
url: /it/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() metodo


Il tempo in cui il documento è stato firmato. Solo lettura [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Osservazioni



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

## Vedi anche

* Classe [DateTime](../../../system/datetime/)
* Classe [DigitalSignature](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)