---
title: get_SignTime()
second_title: Aspose.Slides para la referencia de la API de C++
description: "El tiempo en que el documento fue firmado. Solo lectura System::DateTime."
type: docs
weight: 27
url: /es/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() método


El tiempo en que el documento fue firmado. Solo lectura [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Ver también

* Clase [DateTime](../../../system/datetime/)
* Clase [IDigitalSignature](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)