---
title: get_ExportHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.
type: docs
weight: 27
url: /fr/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() méthode


Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Voir aussi

* Classe [IGifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)