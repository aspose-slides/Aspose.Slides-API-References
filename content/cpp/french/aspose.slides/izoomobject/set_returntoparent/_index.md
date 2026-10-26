---
title: set_ReturnToParent()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit le comportement de navigation dans le diaporama. Écrire bool. Valeur par défaut: false"
type: docs
weight: 40
url: /fr/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) méthode

Définit le comportement de navigation dans le diaporama. Écrire **bool**. Valeur par défaut: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Remarques

La valeur true de la propriété indique le comportement de navigation retour au parent dans le diaporama.

Exemple:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Voir aussi

* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)