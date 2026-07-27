---
title: get_Sound()
second_title: Referencia de API de Aspose.Slides para C++
description: Sonido incrustado definido para el efecto. Lea IAudio.
type: docs
weight: 170
url: /es/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() método

Sonido incrustado definido para el efecto. Lea [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Comentarios



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Obtiene la secuencia de efectos para la diapositiva
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrae el sonido del efecto en una matriz de bytes
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudio](../../../aspose.slides/iaudio/)
* Clase [IEffect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)