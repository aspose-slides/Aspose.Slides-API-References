---
title: IChart
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayttaki grafik tabloyu temsil eder.
type: docs
weight: 1720
url: /tr/aspose.slides.charts/ichart/
---
## IChart arayüzü

Bir slayttaki grafik tablosunu temsil eder.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almayı sağlar. Salt okunur [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzünü almayı sağlar. Salt okunur [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | IOverrideThemeable arayüzünü döndürür. Salt okunur [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Grafik eksenlerine erişim sağlar. Salt okunur [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | 3D grafiğin arka duvarının biçimini değiştirmeyi sağlayan bir nesne döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Grafikle ilişkili bağlanmış veya gömülü veri hakkında bilgi döndürür. Salt okunur [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Grafiğin veri tablosunu döndürür. Salt okunur [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Grafik başlığını döndürür veya ayarlar. Salt okunur [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Grafik üzerinde boş hücrelerin nasıl çizileceğini döndürür veya ayarlar. Okunur/yazılabilir [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | 3D grafiğin zemininin biçimini değiştirmeyi sağlayan bir nesne döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Grafiğin bir veri tablosu olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Grafiğin bir gösterge tablosu (legend) olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Grafik alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okunur/yazılabilir Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Grafiğin görünür bir başlığı olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Grafik için bir gösterge tablosu döndürür veya ayarlar. Salt okunur [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Grafiğin çizim alanını temsil eder. Salt okunur [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Yalnızca görünen hücrelerin çizilip çizilmeyeceğini belirler. Hem görünen hem gizli hücrelerin çizilmesi için False ayarlayın. Okunur/yazılabilir Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Grafiğin 3D dönüşünü döndürür. Salt okunur [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Grafiğin maksimum değer üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/yazılabilir Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | 3D grafiğin yan duvarının biçimini değiştirmeyi sağlayan bir nesne döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Grafik stilini döndürür veya ayarlar. Okunur/yazılabilir [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Grafik türünü döndürür veya ayarlar. Okunur/yazılabilir [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Grafiğin üstüne çizilen şekilleri belirler. Salt okunur [`IGroupShape`](../../aspose.slides/igroupshape). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Grafik öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumunu (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir. |

### Ayrıca Bakınız

* arayüz [IFormattedTextContainer](../iformattedtextcontainer)
* arayüz [IGraphicalObject](../../aspose.slides/igraphicalobject)
* arayüz [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->