---
title: set_Sound()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa el sonido de reproducción del hipervínculo. Escriba IAudio.
type: docs
weight: 196
url: /es/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) método

Representa el sonido de reproducción del hipervínculo. Escriba [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Observaciones


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtener el primer hipervínculo de la forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraer el sonido del hipervínculo en un array de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudio](../../iaudio/)
* Clase [IHyperlink](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)