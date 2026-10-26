---
title: AddGroupShape()
second_title: Référence API Aspose.Slides pour C++
description: Crée une nouvelle forme de groupe vide et l’ajoute à la fin de la collection de formes. Le cadre du groupe\\u2019s s’ajustera automatiquement pour s’adapter à toutes les formes ajoutées.
type: docs
weight: 352
url: /fr/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() méthode

Crée une nouvelle forme de groupe vide et l’ajoute à la fin de la collection de formes. Le cadre du groupe s’ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Valeur de retour

Le [IGroupShape](../../igroupshape/) nouvellement créé.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) méthode

Crée une nouvelle forme de groupe, convertit l’image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Le [ISvgImage](../../isvgimage/) contenant le contenu vectoriel à convertir en formes. |
| x | **float** | La coordonnée x du cadre du groupe, en points. |
| y | **float** | La coordonnée y du cadre du groupe, en points. |
| width | **float** | La largeur du cadre du groupe, en points. |
| height | **float** | La hauteur du cadre du groupe, en points. |

### Valeur de retour

Le [IGroupShape](../../igroupshape/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGroupShape](../../igroupshape/)
* Classe [IShapeCollection](../)
* Classe [ISvgImage](../../isvgimage/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)