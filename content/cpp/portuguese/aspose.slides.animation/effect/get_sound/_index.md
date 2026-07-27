---
title: get_Sound()
second_title: Referência da API Aspose.Slides para C++
description: Som incorporado definido para o efeito. Leia IAudio.
type: docs
weight: 170
url: /pt/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() método

Definido som incorporado para o efeito. Leia [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Observações

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Obtém a sequência de efeitos para o slide
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extrai o som do efeito em array de bytes
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../../aspose.slides/iaudio/)
* Classe [Effect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)