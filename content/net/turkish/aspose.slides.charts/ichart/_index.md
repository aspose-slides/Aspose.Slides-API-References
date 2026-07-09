---
title: IChart
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayt üzerindeki grafik çizelgeyi temsil eder.
type: docs
weight: 1740
url: /tr/aspose.slides.charts/ichart/
---
## IChart arayüzü

Bir slayt üzerindeki grafik çizelgeyi temsil eder.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzüne erişim sağlar. Yalnızca okunabilir [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzüne erişim sağlar. Yalnızca okunabilir [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | IOverrideThemeable arayüzünü döndürür. Yalnızca okunabilir [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Grafik eksenlerine erişim sağlar. Yalnızca okunabilir [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | 3B grafiğin arka duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Grafik ile ilişkili bağlanmış veya gömülü veri hakkında bilgi döndürür. Yalnızca okunabilir [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Grafiğin bir veri tablosunu döndürür. Yalnızca okunabilir [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Grafik başlığını döndürür veya ayarlar. Yalnızca okunabilir [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Grafikte boş hücrelerin nasıl çizileceğini döndürür veya ayarlar. Okunabilir/Yazılabilir [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | 3B grafiğin tabanının biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Grafiğin bir veri tablosu olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Grafiğin bir legend'ı olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Grafik alanının yuvarlatılmış köşelere sahip olacağını belirler. Okunabilir/Yazılabilir Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Grafiğin görünür bir başlığı olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Grafik için bir legend döndürür veya ayarlar. Yalnızca okunabilir [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Grafiğin çizecek alanını temsil eder. Yalnızca okunabilir [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Yalnızca görünür hücrelerin çizilip çizilmeyeceğini belirler. Hem görünür hem gizli hücreleri çizmek için false olur. Okunabilir/Yazılabilir Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Grafiğin 3B dönüşünü döndürür. Yalnızca okunabilir [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Grafiğin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | 3B grafiğin yan duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Grafik stilini döndürür veya ayarlar. Okunabilir/Yazılabilir [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Grafik tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Grafiğin üstüne çizilen şekilleri belirtir. Yalnızca okunabilir [`IGroupShape`](../../aspose.slides/igroupshape). |

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