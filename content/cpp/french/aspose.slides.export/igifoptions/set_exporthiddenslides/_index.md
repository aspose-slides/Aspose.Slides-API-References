---
title: set_ExportHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.
type: docs
weight: 40
url: /fr/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) méthode


Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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