---
title: set_GridSpacing()
second_title: Référence API Aspose.Slides pour C++
description: Définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Écrire float.
type: docs
weight: 105
url: /fr/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) méthode

Définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Écrire **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Remarques

La valeur d'espacement de la grille doit être un nombre positif. La plage de valeurs typique va de 1 mm (2.8349607 points) à 2 pouces (144 points).

Le code d'exemple suivant montre comment modifier l'espacement de la grille dans une présentation PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [ViewProperties](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)