---
title: get_ReturnToParent()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient le comportement de navigation dans le diaporama. Lecture bool. Valeur par défaut: false"
type: docs
weight: 27
url: /fr/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() méthode

Obtient le comportement de navigation dans le diaporama. Lecture **bool**. Valeur par défaut: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Remarques

La valeur vraie de la propriété indique le comportement de retour au parent dans le diaporama.

Exemple:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Voir aussi

* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)