---
title: get_SignTime()
second_title: Aspose.Slides C++ API referencia
description: "A dokumentum aláírásának időpontja. Csak olvasható System::DateTime."
type: docs
weight: 27
url: /hu/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() metódus

A dokumentum aláírásának időpontja. Csak olvasható [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Megjegyzések


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

## Lásd még

* Osztály [DateTime](../../../system/datetime/)
* Osztály [DigitalSignature](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)