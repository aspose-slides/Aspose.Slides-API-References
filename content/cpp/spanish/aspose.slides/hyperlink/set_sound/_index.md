---
title: set_Sound()
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa el sonido de reproducción del hipervínculo. Escriba IAudio.
type: docs
weight: 300
url: /es/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) método


Representa el sonido de reproducción del hipervínculo. Escriba [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first shape hyperlink
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
* Clase [Hyperlink](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)