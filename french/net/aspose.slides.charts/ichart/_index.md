---
title: IChart
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une charte graphique sur une diapositive.
type: docs
weight: 1620
url: /fr/net/aspose.slides.charts/ichart/
---
## IChart interface

Représente une charte graphique sur une diapositive.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface IFormattedTextContainer de base. Lecture seule[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Permet d'obtenir l'interface IGraphicalObject de base. Lecture seule[`IGraphicalObject`](../../aspose.slides/igraphicalobject) . |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Renvoie l'interface IOverrideThemeable. Lecture seule[`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable) . |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Fournir un accès aux axes du graphique. Lecture seule[`IAxesManager`](../iaxesmanager) . |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Renvoie un objet qui permet de changer le format du mur arrière d'un graphique 3D. Lecture seule[`IChartWall`](../ichartwall) . |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Renvoie des informations sur les données liées ou intégrées associées à un graphique. Lecture seule[`IChartData`](../ichartdata) . |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Renvoie une table de données d'un graphique. Lecture seule[`IDataTable`](../idatatable) . |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Renvoie ou définit un titre de graphique Lecture seule[`IChartTitle`](../icharttitle) . |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture[`DisplayBlanksAsType`](../displayblanksastype) . |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Renvoie un objet qui permet de changer le format du sol d'un graphique 3D. Lecture seule[`IChartWall`](../ichartwall) . |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Détermine si un graphique a une table de données. Lecture/écritureBoolean . |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Détermine si un graphique a une légende. Lecture/écritureBoolean . |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Spécifie que la zone du graphique doit avoir des coins arrondis. Lecture/écritureBoolean . |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Détermine si un graphique a un titre visible. Lecture/écritureBoolean . |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Renvoie ou définit une légende pour un graphique. Lecture seule[`ILegend`](../ilegend) . |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Représente la zone de tracé d'un graphique. Lecture seule[`IChartPlotArea`](../ichartplotarea) . |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Détermine si les seules cellules visibles sont tracées. False pour tracer les cellules visibles et masquées. Lecture/écritureBoolean . |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Renvoie une rotation 3D d'un graphique. Lecture seule[`IRotation3D`](../irotation3d) . |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Spécifie que les étiquettes de données sur le maximum du graphique doivent être affichées. Lecture/écritureBoolean . |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Renvoie un objet qui permet de changer le format de la paroi latérale d'un graphique 3D. Lecture seule[`IChartWall`](../ichartwall) . |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Renvoie ou définit le style de graphique. Lecture/écriture[`StyleType`](../styletype) . |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Renvoie ou définit le type de graphique. Lecture/écriture[`ChartType`](../charttype) . |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Spécifiez les formes dessinées en haut du graphique. Lecture seule[`IGroupShape`](../../aspose.slides/igroupshape) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis. IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Voir également

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
