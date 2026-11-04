---
title: IChart
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slaytta bulunan grafik bir çizelgeyi temsil eder.
type: docs
weight: 1760
url: /tr/aspose.slides.charts/ichart/
---
## IChart arayüzü

Bir slayttaki grafik çizelgeyi temsil eder.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almaya izin verir. Salt okunur [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzünü almaya izin verir. Salt okunur [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | IOverrideThemeable arayüzünü döndürür. Salt okunur [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Çizelge eksenlerine erişim sağlar. Salt okunur [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | 3D çizelgenin arka duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Bir çizelgeyle ilişkili bağlanmış veya gömülü veri hakkında bilgileri döndürür. Salt okunur [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Bir çizelgenin veri tablosunu döndürür. Salt okunur [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Çizelge başlığını döndürür veya ayarlar. Salt okunur [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Çizelgede boş hücrelerin nasıl çizileceğini döndürür veya ayarlar. Okunur/yazılır [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | 3D çizelgenin zemininin biçimini değiştirmeye izin veren bir nesneyi döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bir çizelgenin veri tablosu olup olmadığını belirler. Okunur/yazılır Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bir çizelgenin açıklama kutusu (legend) olup olmadığını belirler. Okunur/yazılır Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Çizelge alanının yuvarlatılmış köşelere sahip olmasını belirtir. Okunur/yazılır Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bir çizelgenin görünür başlığı olup olmadığını belirler. Okunur/yazılır Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Bir çizelge için açıklama kutusunu (legend) döndürür veya ayarlar. Salt okunur [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Bir çizelgenin çizim alanını temsil eder. Salt okunur [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Yalnızca görünür hücrelerin çizilip çizilmeyeceğini belirler. Hem görünür hem gizli hücreleri çizmek için false. Okunur/yazılır Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Bir çizelgenin 3D dönüşünü döndürür. Salt okunur [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/yazılır Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | 3D çizelgenin yan duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Salt okunur [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Çizelge stilini döndürür veya ayarlar. Okunur/yazılır [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Çizelge tipini döndürür veya ayarlar. Okunur/yazılır [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Çizelgenin üstünde çizilen şekilleri belirtir. Salt okunur [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metodlar

| Ad | Açıklama |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumunu (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir. |

### Ayrıca Bakınız

* arayüz [IFormattedTextContainer](../iformattedtextcontainer)
* arayüz [IGraphicalObject](../../aspose.slides/igraphicalobject)
* arayüz [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->