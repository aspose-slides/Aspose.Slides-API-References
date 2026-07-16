---
title: set_AnimateTransitions()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'option d'animation des transitions. Écrire bool.
type: docs
weight: 14
url: /fr/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) méthode


Définit l'option d'animation des transitions. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Voir aussi

* Classe [IHtml5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)