---
title: get_ExportHiddenSlides()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.
type: docs
weight: 27
url: /fr/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() méthode


Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Voir aussi

* Classe [GifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)