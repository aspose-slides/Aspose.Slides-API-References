---
title: set_Sound()
second_title: Referência da API Aspose.Slides para C++
description: Define som incorporado para o efeito. Escreva IAudio.
type: docs
weight: 183
url: /pt/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) método

Define som incorporado para o efeito. Escreva [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
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

    // Extrai o som do efeito em um array de bytes
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudio](../../../aspose.slides/iaudio/)
* Classe [IEffect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)