---
title: IChart
second_title: Aspose.Sildes per .NET API Reference
description: Rappresenta un grafico su una diapositiva.
type: docs
weight: 1740
url: /it/aspose.slides.charts/ichart/
---
## Interfaccia IChart

Rappresenta un grafico su una diapositiva.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Consente di ottenere l'interfaccia base IFormattedTextContainer. Sola lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Consente di ottenere l'interfaccia base IGraphicalObject. Sola lettura [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Restituisce l'interfaccia IOverrideThemeable. Sola lettura [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Fornisce l'accesso agli assi del grafico. Sola lettura [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Restituisce informazioni sui dati collegati o incorporati associati a un grafico. Sola lettura [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Restituisce una tabella dati di un grafico. Sola lettura [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Restituisce o imposta il titolo del grafico. Sola lettura [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Restituisce o imposta il modo di tracciare le celle vuote su un grafico. Lettura/Scrittura [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Determina se un grafico ha una tabella dati. Lettura/Scrittura Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Determina se un grafico ha una legenda. Lettura/Scrittura Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Specifica che l'area del grafico deve avere angoli arrotondati. Lettura/Scrittura Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Determina se un grafico ha un titolo visibile. Lettura/Scrittura Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Restituisce o imposta una legenda per il grafico. Sola lettura [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Rappresenta l'area di tracciamento di un grafico. Sola lettura [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili che quelle nascoste. Lettura/Scrittura Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Restituisce una rotazione 3D di un grafico. Sola lettura [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Specifica che le etichette dati al di sopra del valore massimo del grafico devono essere mostrate. Lettura/Scrittura Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Restituisce o imposta lo stile del grafico. Lettura/Scrittura [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Restituisce o imposta il tipo di grafico. Lettura/Scrittura [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specifica le forme disegnate sopra il grafico. Sola lettura [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcola i valori effettivi degli elementi del grafico. I valori effettivi includono la posizione degli elementi che implementano l'interfaccia IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e i valori effettivi degli assi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Vedi anche

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->