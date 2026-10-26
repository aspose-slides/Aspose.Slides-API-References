---
title: IChart
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente un graphique sur une diapositive.
type: docs
weight: 1740
url: /fr/aspose.slides.charts/ichart/
---
## interface IChart

Représente un graphique sur une diapositive.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Permet d'obtenir l'interface de base IGraphicalObject. Lecture seule [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Renvoie l'interface IOverrideThemeable. Lecture seule [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Fournit l'accès aux axes du diagramme. Lecture seule [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Renvoie un objet qui permet de modifier le format du mur arrière d'un diagramme 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Renvoie les informations sur les données liées ou incorporées associées à un diagramme. Lecture seule [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Renvoie un tableau de données d'un diagramme. Lecture seule [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Renvoie ou définit le titre du diagramme. Lecture seule [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Renvoie ou définit la façon de tracer les cellules vides sur un diagramme. Lecture/écriture [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Renvoie un objet qui permet de modifier le format du plancher d'un diagramme 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Détermine si le diagramme possède un tableau de données. Lecture/écriture Booléen. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Détermine si le diagramme possède une légende. Lecture/écriture Booléen. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Spécifie que la zone du diagramme doit avoir des coins arrondis. Lecture/écriture Booléen. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Détermine si le diagramme possède un titre visible. Lecture/écriture Booléen. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Renvoie ou définit une légende pour le diagramme. Lecture seule [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Représente la zone de tracé d'un diagramme. Lecture seule [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Détermine si seules les cellules visibles sont tracées. Faux pour tracer à la fois les cellules visibles et cachées. Lecture/écriture Booléen. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Renvoie une rotation 3D d'un diagramme. Lecture seule [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Spécifie que les étiquettes de données au-dessus du maximum du diagramme doivent être affichées. Lecture/écriture Booléen. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Renvoie un objet qui permet de modifier le format du mur latéral d'un diagramme 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Renvoie ou définit le style du diagramme. Lecture/écriture [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Renvoie ou définit le type du diagramme. Lecture/écriture [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Spécifie les formes dessinées au-dessus du diagramme. Lecture seule [`IGroupShape`](../../aspose.slides/igroupshape). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcule les valeurs réelles des éléments du diagramme. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->