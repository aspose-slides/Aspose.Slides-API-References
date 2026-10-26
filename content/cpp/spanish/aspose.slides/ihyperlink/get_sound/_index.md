---
title: get_Sound()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa el sonido reproducido del hipervínculo. Leer IAudio.
type: docs
weight: 183
url: /es/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() método


Representa el sonido reproducido del hipervínculo. Leer [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtener el hipervínculo de la primera forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraer el sonido del hipervínculo en un arreglo de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudio](../../iaudio/)
* Clase [IHyperlink](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)