---
title: set_IncludeHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient ou définit si les diapositives masquées doivent être incluses.
type: docs
weight: 40
url: /fr/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) méthode


Obtient ou définit si les diapositives masquées doivent être incluses.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## Voir aussi

* Classe [PresentationAnimationsGenerator](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)