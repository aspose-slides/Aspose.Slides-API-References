---
title: Axis
second_title: Aspose.Sildes için .NET API Referansı
description: Grafik eksenini temsil eden nesneyi kapsüller.
type: docs
weight: 1160
url: /tr/aspose.slides.charts/axis/
---
## Axis sınıfı

Bir grafiğin eksenini temsil eden nesneyi kapsüller.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Özkellikler

| Ad | Açıklama |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Eksenin gerçek ana birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Eksenin gerçek küçük birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Kategori ekseninin (gruplama) toplama tipini temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklere uygulanmaz. Okunabilir/Yazılabilir Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Kategori ekseninin tipini belirtir. Okunabilir/Yazılabilir [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Üst grafiği döndürür. Yalnızca okunabilir [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Düşey eksenin onu kestiği eksen üzerindeki noktayı temsil eder. Okunabilir/Yazılabilir Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Diğer eksenin geçtiği belirtilen eksendeki CrossType'ı temsil eder. Okunabilir/Yazılabilir [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Değer ekseni için görüntü birimlerinin ölçek değerini belirtir. Okunabilir/Yazılabilir [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Eksenin biçimini temsil eder. Yalnızca okunabilir [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bir eksenin görünür bir başlığı olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Otomatik taşma kutusu değerini belirtir. False ise: OverflowBin özelliğini kullanın. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Otomatik işaret etiketi boşluk değerini belirtir. False ise: TickLabelSpacing özelliğini kullanın. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Otomatik işaret işaretleri boşluk değerini belirtir. False ise: TickMarksSpacing özelliğini kullanın. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Otomatik eksik akış kutusu değerini belirtir. False ise: UnderflowBin özelliğini kullanın. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Değer ekseni ölçek tipinin logaritmik olup olmadığını temsil eder. Okunabilir/Yazılabilir Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Biçimin bağlanmış kaynak veri olup olmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | MS PowerPoint'in veri noktalarını sondan başa çizmeyi temsil eder. Okunabilir/Yazılabilir Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Eksik akış kutusunun uygulanıp uygulanmadığını belirtir. Eksik akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Eksenin görünür olup olmadığını temsil eder. Okunabilir/Yazılabilir Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunabilir/Yazılabilir UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunabilir/Yazılabilir Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Bir grafik eksenindeki ana ızgara çizgileri biçimini temsil eder. Yalnızca okunabilir [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Belirtilen eksen için ana işaret biçimini temsil eder. Okunabilir/Yazılabilir [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Tarih veya değer ekseni için ana birimleri temsil eder. Okunabilir/Yazılabilir Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Tarih ekseni için ana birim ölçeğini temsil eder. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Değer eksenindeki maksimum değeri temsil eder. Okunabilir/Yazılabilir Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Bir grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder. Yalnızca okunabilir [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Belirtilen eksen için küçük işaret tipini temsil eder. Okunabilir/Yazılabilir [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Tarih veya değer ekseni için küçük birimleri temsil eder. Okunabilir/Yazılabilir Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Tarih ekseni için ana birim ölçeğini temsil eder. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Değer eksenindeki minimum değeri temsil eder. Okunabilir/Yazılabilir Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Axis Labels için biçim dizesini temsil eder. Okunabilir/Yazılabilir String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Taşma kutusu için özel değeri belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Eksenin konumunu temsil eder. Okunabilir/Yazılabilir [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Ana ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Yalnızca okunabilir Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Küçük ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın. Yalnızca okunabilir Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Metin biçimini temsil eder. Yalnızca okunabilir [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Belirtilen eksende işaret etiketi konumunu temsil eder. Okunabilir/Yazılabilir [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | İşaret etiketlerinin döndürme açısını temsil eder. Okunabilir/Yazılabilir Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Çizilen etiketler arasında kaç işaret etiketi atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunabilir/Yazılabilir UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Sonraki işaret çizilmeden önce kaç işaret atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunabilir/Yazılabilir UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Eksenin başlığını alır. Yalnızca okunabilir [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Eksik akış kutusu için özel değeri belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType özelliğini eksen verilerine dayalı otomatik belirlenen bir değerle ayarlar. |

### Ayrıca Bakınız

* sınıf [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* sınıf [AxesManager](../axesmanager)
* arayüz [IAxis](../iaxis)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->