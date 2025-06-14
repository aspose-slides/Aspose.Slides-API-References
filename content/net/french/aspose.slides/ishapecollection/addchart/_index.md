---
title: AddChart
second_title: Aspose.Slides pour la référence API .NET
description: Crée un nouveau graphique, l'initialise avec des données et des paramètres d'échantillons, et l'ajoute à la fin de la collection.
type: docs
weight: 70
url: /fr/aspose.slides/ishapecollection/addchart/
---

## AddChart(ChartType, float, float, float, float) {#addchart}

Crée un nouveau graphique, l'initialise avec des données et des paramètres d'échantillons, et l'ajoute à la fin de la collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | ChartType | Type de graphique. |
| x | Single | Coordonnée X d'un nouveau graphique. |
| y | Single | Coordonnée Y d'un nouveau graphique. |
| width | Single | Largeur du graphique. |
| height | Single | Hauteur du graphique. |

### Valeur de retour

Graphique créé.

### Voir aussi

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Crée un nouveau graphique et l'ajoute à la fin de la collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | ChartType | Type de graphique. |
| x | Single | Coordonnée X d'un nouveau graphique. |
| y | Single | Coordonnée Y d'un nouveau graphique. |
| width | Single | Largeur du graphique. |
| height | Single | Hauteur du graphique. |
| initWithSample | Boolean | Si vrai, le nouveau graphique sera initialisé avec des données et des paramètres d'échantillons. Si faux, le nouveau graphique n'aura pas de séries et des paramètres minimum. Dans ce cas, la création du graphique sera plus rapide. |

### Valeur de retour

Graphique créé.

### Voir aussi

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->