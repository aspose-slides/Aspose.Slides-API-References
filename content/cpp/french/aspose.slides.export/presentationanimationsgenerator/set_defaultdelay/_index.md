---
title: set_DefaultDelay()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le temps de retard par défaut [ms].
type: docs
weight: 14
url: /fr/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) méthode


Définit le temps de retard par défaut [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Voir aussi

* Classe [PresentationAnimationsGenerator](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)