---
title: AddAutoShape
second_title: Aspose.Slides pour la référence API .NET
description: Crée un nouvel AutoShape, l'ajuste à partir du modèle par défaut et l'ajoute à la fin de la collection.
type: docs
weight: 60
url: /fr/aspose.slides/ishapecollection/addautoshape/
---

## AddAutoShape(ShapeType, float, float, float, float) {#addautoshape}

Crée un nouvel AutoShape, l'ajuste à partir du modèle par défaut et l'ajoute à la fin de la collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | ShapeType | Le [`ShapeType`](../../shapetype) de la forme. |
| x | Single | La coordonnée X pour le côté gauche du cadre de la forme. |
| y | Single | La coordonnée Y pour le côté supérieur du cadre de la forme. |
| width | Single | La largeur du cadre de la forme. |
| height | Single | La hauteur du cadre de la forme. |

### Valeur de retour

Objet AutoShape créé.

### Voir Aussi

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddAutoShape(ShapeType, float, float, float, float, bool) {#addautoshape_1}

Crée un nouvel AutoShape et l'ajoute à la fin de la collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | ShapeType | Le [`ShapeType`](../../shapetype) de la forme. |
| x | Single | La coordonnée X pour le côté gauche du cadre de la forme. |
| y | Single | La coordonnée Y pour le côté supérieur du cadre de la forme. |
| width | Single | La largeur du cadre de la forme. |
| height | Single | La hauteur du cadre de la forme. |
| createFromTemplate | Boolean | Si vrai, la nouvelle forme sera ajustée à partir du modèle par défaut. Un nom non vide, un style simple, un texte centré seront assignés à la nouvelle forme. Si faux, alors toutes les valeurs des propriétés de la nouvelle forme auront des valeurs par défaut. |

### Valeur de retour

Objet AutoShape créé.

### Voir Aussi

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->