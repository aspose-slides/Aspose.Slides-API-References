---
title: set_Sound()
second_title: Referencia de API de Aspose.Slides para C++
description: Define el sonido incrustado para el efecto. Escriba IAudio.
type: docs
weight: 183
url: /es/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) método


Define el sonido incrustado para el efecto. Escriba [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Obtiene la secuencia de efectos de la diapositiva
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