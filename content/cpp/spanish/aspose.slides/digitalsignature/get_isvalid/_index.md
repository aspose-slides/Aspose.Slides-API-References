---
title: get_IsValid()
second_title: Referencia de la API de Aspose.Slides para C++
description: Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura bool.
type: docs
weight: 14
url: /es/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() método


Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Ver también

* Clase [DigitalSignature](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)