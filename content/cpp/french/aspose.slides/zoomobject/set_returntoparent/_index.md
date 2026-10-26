---
title: set_ReturnToParent()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit le comportement de navigation dans le diaporama. Écrire bool. Valeur par défaut: false"
type: docs
weight: 40
url: /fr/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) méthode

Définit le comportement de navigation dans le diaporama. Écrire **bool**. Valeur par défaut : false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Remarques

La valeur vraie de la propriété spécifie le comportement de retour au parent dans le diaporama.

Exemple :
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Voir aussi

* classe [ZoomObject](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)