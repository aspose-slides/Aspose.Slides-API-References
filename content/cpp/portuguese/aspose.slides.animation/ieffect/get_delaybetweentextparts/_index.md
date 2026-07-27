---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides para C++ Referência da API
description: Define um atraso entre as partes de texto animadas (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Lê float.
type: docs
weight: 300
url: /pt/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() método


Define um atraso entre as partes de texto animadas (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Lê **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
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

## Veja Também

* Classe [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)