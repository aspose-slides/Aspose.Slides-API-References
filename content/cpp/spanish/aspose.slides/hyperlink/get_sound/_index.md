---
title: get_Sound()
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa el sonido en reproducción del hipervínculo. Lea IAudio.
type: docs
weight: 287
url: /es/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() método


Representa el sonido en reproducción del hipervínculo. Leer [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```


## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtener el primer hipervínculo de la forma
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Extraer el sonido del hipervínculo en una matriz de bytes
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudio](../../iaudio/)
* Clase [Hyperlink](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)