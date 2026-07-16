---
title: set_AnimateShapes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'option d'animation des formes. Écrire bool.
type: docs
weight: 40
url: /fr/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) méthode


Définit l'option d'animation des formes. Écrire **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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