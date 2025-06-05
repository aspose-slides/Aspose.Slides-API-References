---
title: IChart
second_title: Aspose.Sildes pour la référence de l'API .NET
description: Représente un graphique sur une diapositive.
type: docs
weight: 1660
url: /fr/aspose.slides.charts/ichart/
---

## Interface IChart

Représente un graphique sur une diapositive.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Permet d'obtenir l'interface de base IGraphicalObject. Lecture seule [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Retourne l'interface IOverrideThemeable. Lecture seule [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Fournit l'accès aux axes du graphique. Lecture seule [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Retourne un objet qui permet de changer le format du mur arrière d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Retourne des informations sur les données liées ou intégrées associées à un graphique. Lecture seule [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Retourne une table de données d'un graphique. Lecture seule [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Retourne ou définit un titre de graphique. Lecture seule [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Retourne ou définit la manière de tracer les cellules vides sur un graphique. Lecture/écriture [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Retourne un objet qui permet de changer le format du sol d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Détermine si un graphique a une table de données. Lecture/écriture Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Détermine si un graphique a une légende. Lecture/écriture Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écriture Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Détermine si un graphique a un titre visible. Lecture/écriture Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Retourne ou définit une légende pour un graphique. Lecture seule [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Représente la zone de tracé d'un graphique. Lecture seule [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Détermine si seules les cellules visibles sont tracées. Faux pour tracer à la fois les cellules visibles et cachées. Lecture/écriture Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Retourne une rotation 3D d'un graphique. Lecture seule [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Retourne un objet qui permet de changer le format du mur latéral d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Retourne ou définit le style du graphique. Lecture/écriture [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Retourne ou définit le type de graphique. Lecture/écriture [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Spécifie les formes dessinées au-dessus du graphique. Lecture seule [`IGroupShape`](../../aspose.slides/igroupshape). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->