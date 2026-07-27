---
title: set_DelayBetweenTextParts()
second_title: Referência da API Aspose.Slides para C++
description: Define um atraso entre partes de texto animadas (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Escreva float.
type: docs
weight: 313
url: /pt/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) método


Define um atraso entre partes de texto animadas (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Escreva **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Ver também

* Classe [Effect](../)
* Espaço de nomes [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)