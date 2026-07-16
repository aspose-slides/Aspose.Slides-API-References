---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides pour la référence API C++
description: Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.
type: docs
weight: 40
url: /fr/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) méthode


Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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