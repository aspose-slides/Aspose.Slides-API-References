---
title: set_Sound()
second_title: Referencia de la API de Aspose.Slides para C++
description: Define el sonido incrustado para el efecto. Escriba IAudio.
type: docs
weight: 183
url: /es/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) método

Define el sonido incrustado para el efecto. Escriba [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Observaciones



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

    // Extrae el sonido del efecto en un arreglo de bytes
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudio](../../../aspose.slides/iaudio/)
* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)