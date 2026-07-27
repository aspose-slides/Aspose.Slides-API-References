---
title: get_SignTime()
second_title: Referencia de la API de Aspose.Slides para C++
description: "El tiempo en que el documento fue firmado. Solo lectura System::DateTime."
type: docs
weight: 27
url: /es/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() método


El tiempo en que el documento fue firmado. Solo lectura [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Observaciones



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

## Ver también

* Clase [DateTime](../../../system/datetime/)
* Clase [DigitalSignature](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)