---
title: get_AnimateTransitions()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'option d'animation des transitions. Lecture bool.
type: docs
weight: 1
url: /fr/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() méthode


Renvoie l'option d'animation des transitions. Lecture **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Remarques


Exemple: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Voir aussi

* Classe [Html5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)