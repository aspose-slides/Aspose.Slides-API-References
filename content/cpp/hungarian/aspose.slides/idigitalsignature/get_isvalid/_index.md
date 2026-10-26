---
title: get_IsValid()
second_title: Aspose.Slides C++ API referencia
description: Ha ez a digitális aláírás érvényes, és a dokumentumot nem módosították, ez az érték igaz lesz. Csak olvasható bool.
type: docs
weight: 14
url: /hu/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() metódus


Ha ez a digitális aláírás érvényes, és a dokumentumot nem módosították, ez az érték igaz lesz. Csak olvasható **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Megjegyzés



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Lásd még

* Osztály [IDigitalSignature](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)