---
title: IAxis
second_title: Aspose.Sildes için .NET API Referansı
description: Grafik eksenini temsil eden nesneyi kapsar.
type: docs
weight: 1720
url: /tr/aspose.slides.charts/iaxis/
---
## IAxis arayüz

Çizginin eksenini temsil eden nesneyi kapsar.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Eksenin gerçek büyük birimini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Eksenin gerçek büyük birim ölçeğini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Eksenin gerçek küçük birimini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Kategori ekseninin toplama tipini (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almayı sağlar. Yalnızca okunur [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklere uygulanmaz. Okunur/yazılabilir Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur/yazılabilir [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Kategori ekseninin tipini belirtir. Okunur/yazılabilir [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Perpendiküler eksenin kesiştiği eksendeki noktayı temsil eder. Okunur/yazılabilir Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. Okunur/yazılabilir [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Değer ekseni için gösterim birimlerinin ölçek değerini belirtir. Okunur/yazılabilir [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Eksenin biçimini temsil eder. Yalnızca okunur [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bir eksenin görünür başlığı olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/yazılabilir Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/yazılabilir Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunur/yazılabilir Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. Okunur/yazılabilir Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Otomatik taşma kutusu değerini belirtir. False ise: OverflowBin özelliğini kullanın. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Otomatik tik etiket aralığı değerini belirtir. False ise: TickLabelSpacing özelliğini kullanın. Okunur/yazılabilir Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Otomatik tik işaretleri aralığı değerini belirtir. False ise: TickMarksSpacing özelliğini kullanın. Okunur/yazılabilir Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Otomatik eksik akış kutusu değerini belirtir. False ise: UnderflowBin özelliğini kullanın. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. Okunur/yazılabilir Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Biçimin bağlantılı kaynak verisi olup olmadığını gösterir. Okunur/yazılabilir Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | MS PowerPoint'in veri noktalarını sonundan birine doğru çizerse temsil eder. Okunur/yazılabilir Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Eksik akış kutusunun uygulanıp uygulanmadığını belirtir. Eksik akış kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Eksenin görünür olup olmadığını temsil eder. Okunur/yazılabilir Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Etiketlerin eksenden uzaklık değerini belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunur/yazılabilir UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunur/yazılabilir Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Bir grafik eksenindeki büyük ızgara çizgileri biçimini temsil eder. Yalnızca okunur [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Belirtilen eksen için büyük tik işaretinin tipini temsil eder. Okunur/yazılabilir [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Tarih veya değer ekseni için büyük birimleri temsil eder. Okunur/yazılabilir Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/yazılabilir [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Değer eksenindeki maksimum değeri temsil eder. Okunur/yazılabilir Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Bir grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder. Yalnızca okunur [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Belirtilen eksen için küçük tik işaretinin tipini temsil eder. Okunur/yazılabilir [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Tarih veya değer ekseni için küçük birimleri temsil eder. Okunur/yazılabilir Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Tarih ekseni için büyük birim ölçeğini temsil eder. Okunur/yazılabilir [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Değer eksenindeki minimum değeri temsil eder. Okunur/yazılabilir Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Eksen Etiketleri için biçim dizesini temsil eder. Okunur/yazılabilir String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Taşma kutusu özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Eksenin konumunu temsil eder. Okunur/yazılabilir [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Büyük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Yalnızca okunur Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Küçük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Yalnızca okunur Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Belirtilen eksende tik işareti etiketlerinin konumunu temsil eder. Okunur/yazılabilir [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Tik etiketlerinin dönüş açısını temsil eder. Okunur/yazılabilir Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Çizilen etiketler arasında kaç tik etiketinin atlanacağını belirtir. Okunur/yazılabilir UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Bir sonraki tik işaretinin çizilmeden önce kaç tik işaretinin atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunur/yazılabilir UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Eksen başlığını alır. Yalnızca okunur [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Eksik akış kutusu özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType özelliğini eksen verilerine göre otomatik olarak belirlenen bir değerle ayarlar. |

### Ayrıca Bakınız

* arayüz [IFormattedTextContainer](../iformattedtextcontainer)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->