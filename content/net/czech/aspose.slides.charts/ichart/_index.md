---
title: IChart
second_title: Aspose.Sildes pro .NET API Reference
description: Representuje grafický diagram na snímku.
type: docs
weight: 1740
url: /cs/aspose.slides.charts/ichart/
---
## IChart rozhraní

Representuje grafický diagram na snímku.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Umožňuje získat základní rozhraní IFormattedTextContainer. Pouze pro čtení [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Umožňuje získat základní rozhraní IGraphicalObject. Pouze pro čtení [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Vrací rozhraní IOverrideThemeable. Pouze pro čtení [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Poskytuje přístup k osám diagramu. Pouze pro čtení [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Vrací objekt, který umožňuje měnit formát zadní stěny 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Vrací informace o propojených nebo vložených datech souvisejících s diagramem. Pouze pro čtení [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Vrací datovou tabulku diagramu. Pouze pro čtení [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Vrací nebo nastavuje název diagramu. Pouze pro čtení [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu. Čtení/Zápis [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Vrací objekt, který umožňuje měnit formát podlahy 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Určuje, zda má diagram datovou tabulku. Čtení/Zápis Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Určuje, zda má diagram legendu. Čtení/Zápis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Určuje, zda má oblast diagramu zaoblené rohy. Čtení/Zápis Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Určuje, zda má diagram viditelný název. Čtení/Zápis Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Vrací nebo nastavuje legendu diagramu. Pouze pro čtení [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Reprezentuje oblast vykreslování diagramu. Pouze pro čtení [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Určuje, zda jsou vykresleny pouze viditelné buňky. False k vykreslení jak viditelných, tak skrytých buněk. Čtení/Zápis Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Vrací 3D rotaci diagramu. Pouze pro čtení [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Určuje, že se mají zobrazovat popisky dat nad maximem diagramu. Čtení/Zápis Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Vrací objekt, který umožňuje měnit formát boční stěny 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Vrací nebo nastavuje styl diagramu. Čtení/Zápis [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Vrací nebo nastavuje typ diagramu. Čtení/Zápis [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Určuje tvary kreslené nad diagramem. Pouze pro čtení [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metody

| Název | Popis |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Vypočítá skutečné hodnoty prvků diagramu. Skutečné hodnoty zahrnují polohu prvků, které implementují rozhraní IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Viz také

* rozhraní [IFormattedTextContainer](../iformattedtextcontainer)
* rozhraní [IGraphicalObject](../../aspose.slides/igraphicalobject)
* rozhraní [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->