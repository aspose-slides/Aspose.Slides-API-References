---
title: get_GridSpacing()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture float.
type: docs
weight: 92
url: /fr/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() méthode


Renvoie l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Remarques


La valeur d'espacement de la grille doit être un nombre positif. La plage de valeur typique va de 1 mm (2.8349607 points) à 2 pouces (144 points). 

Le code d'exemple suivant montre comment modifier l'espacement de la grille dans une présentation PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IViewProperties](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)