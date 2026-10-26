---
title: get_AnimateShapes()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'option d'animation des formes. Lecture bool.
type: docs
weight: 27
url: /fr/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() méthode

Renvoie l'option d'animation des formes. Lecture **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Remarques

Exemple :
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## Voir aussi

* Classe [Html5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)