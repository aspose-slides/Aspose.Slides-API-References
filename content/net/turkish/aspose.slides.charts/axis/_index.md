---
title: Axis
second_title: Aspose.Sildes için .NET API Referansı
description: Bir grafiğin eksenini temsil eden nesneyi kapsüller.
type: docs
weight: 1180
url: /tr/aspose.slides.charts/axis/
---
## Axis sınıfı

Bir chart'ın eksenini temsil eden nesneyi kapsüller.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Özellikler

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Eksenin gerçek ana birimini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Eksenin gerçek ikincil birimini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Eksenin gerçek ikincil birim ölçeğini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() yöntemini çağırın. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Kategori ekseninin (binleme) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılabilir. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Değer ekseninin kategori eksenini kategoriler arasından geçip geçmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-B grafiklere uygulanmaz. Okunabilir/yazılabilir Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunabilir/yazılabilir [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılabilir. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Kategori ekseninin türünü belirtir. Okunabilir/yazılabilir [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Üst chart'ı döndürür. Salt-okunur [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Eksenin dik eksenle kesiştiği noktayı temsil eder. Okunabilir/yazılabilir Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Diğer eksenin kesildiği belirtilen eksende CrossType'ı temsil eder. Okunabilir/yazılabilir [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Değer eksenindeki gösterim birimlerinin ölçeklendirme değerini belirtir. Okunabilir/yazılabilir [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Eksenin biçimini temsil eder. Salt-okunur [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bir eksenin görünür başlığa sahip olup olmadığını belirler. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Eksenin ikincil biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Otomatik taşma bin değerini belirtir. False ise: OverflowBin özelliğini kullanın. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Otomatik işaret etiketi aralığı değerini belirtir. False ise: TickLabelSpacing özelliğini kullanın. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Otomatik işaret çizgileri aralığı değerini belirtir. False ise: TickMarksSpacing özelliğini kullanın. Okunabilir/yazılabilir Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Otomatik alt akış bin değerini belirtir. False ise: UnderflowBin özelliğini kullanın. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. Okunabilir/yazılabilir Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Biçimin bağlantılı kaynak veri olup olmadığını gösterir. Okunabilir/yazılabilir Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | MS PowerPoint'in veri noktalarını sondan ilkine çizip çizmediğini temsil eder. Okunabilir/yazılabilir Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Alt akış bininin uygulanıp uygulanmadığını belirtir. Alt akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Eksenin görünür olup olmadığını temsil eder. Okunabilir/yazılabilir Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunabilir/yazılabilir UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunabilir/yazılabilir Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Bir chart eksenindeki ana ızgara çizgileri biçimini temsil eder. Salt-okunur [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Belirtilen eksen için ana işaret çubuğu tipini temsil eder. Okunabilir/yazılabilir [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Tarih veya değer ekseni için ana birimleri temsil eder. Okunabilir/yazılabilir Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Tarih ekseni için ana birim ölçeğini temsil eder. Okunabilir/yazılabilir [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Değer eksenindeki maksimum değeri temsil eder. Okunabilir/yazılabilir Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Bir chart eksenindeki ikincil ızgara çizgileri biçimini temsil eder. Salt-okunur [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Belirtilen eksen için ikincil işaret çubuğu tipini temsil eder. Okunabilir/yazılabilir [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Tarih veya değer ekseni için ikincil birimleri temsil eder. Okunabilir/yazılabilir Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Tarih ekseni için ana birim ölçeğini temsil eder. Okunabilir/yazılabilir [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Değer eksenindeki minimum değeri temsil eder. Okunabilir/yazılabilir Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Axis Etiketleri için biçim dizesini temsil eder. Okunabilir/yazılabilir String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılabilir. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Taşma bin özelleştirilmiş değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Eksenin konumunu temsil eder. Okunabilir/yazılabilir [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Ana ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Salt-okunur Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | İkincil ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Salt-okunur Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Metin biçimini temsil eder. Salt-okunur [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Belirtilen eksen üzerindeki işaret çubuğu etiketlerinin konumunu temsil eder. Okunabilir/yazılabilir [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | İşaret etiketlerinin döndürme açısını temsil eder. Okunabilir/yazılabilir Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Çizilen etiketler arasında kaç işaret etiketi atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunabilir/yazılabilir UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Bir sonraki işaret çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunabilir/yazılabilir UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Eksenin başlığını alır. Salt-okunur [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Alt akış bin özelleştirilmiş değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |

## Yöntemler

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType özelliğini, eksen verilerine dayalı otomatik olarak belirlenen bir değerle ayarlar. |

### Ayrıca Bakınız

* sınıf [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* sınıf [AxesManager](../axesmanager)
* arayüz [IAxis](../iaxis)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->