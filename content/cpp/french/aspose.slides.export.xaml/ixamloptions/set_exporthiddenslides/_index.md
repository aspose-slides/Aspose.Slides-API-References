---
title: set_ExportHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si les diapositives masquées seront exportées.
type: docs
weight: 14
url: /fr/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) method

Détermine si les diapositives masquées seront exportées.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Voir aussi

* Classe [IXamlOptions](../)
* Espace de noms [Aspose::Slides::Export::Xaml](../../)
* Bibliothèque [Aspose.Slides](../../../)