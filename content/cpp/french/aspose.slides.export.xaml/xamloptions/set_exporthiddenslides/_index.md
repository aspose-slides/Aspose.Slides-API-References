---
title: set_ExportHiddenSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si les diapositives masquées seront exportées.
type: docs
weight: 14
url: /fr/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) méthode


Détermine si les diapositives masquées seront exportées.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## Voir aussi

* Classe [XamlOptions](../)
* Espace de noms [Aspose::Slides::Export::Xaml](../../)
* Bibliothèque [Aspose.Slides](../../../)