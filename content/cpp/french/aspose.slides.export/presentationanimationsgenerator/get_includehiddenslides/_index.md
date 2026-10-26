---
title: get_IncludeHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient ou définit si les diapositives masquées doivent être incluses.
type: docs
weight: 27
url: /fr/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const méthode


Obtient ou définit si les diapositives masquées doivent être incluses.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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