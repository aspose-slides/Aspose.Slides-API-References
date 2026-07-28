---
title: get_SignTime()
second_title: Aspose.Slides C++ API referencia
description: "A dokumentum aláírásának időpontja. Csak olvasható System::DateTime."
type: docs
weight: 27
url: /hu/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() metódus


A dokumentum aláírásának időpontja. Csak olvasható [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Lásd még

* Osztály [DateTime](../../../system/datetime/)
* Osztály [IDigitalSignature](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)