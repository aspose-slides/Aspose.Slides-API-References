---
title: IAxis
second_title: Aspose.Sildes için .NET API Referansı
description: Grafik eksenini temsil eden nesneyi kapsüller.
type: docs
weight: 1710
url: /tr/aspose.slides.charts/iaxis/
---
## IAxis arayüz

Bir grafiğin eksenini temsil eden nesneyi kapsüler.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Eksenin gerçek büyük birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Eksenin gerçek büyük birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Eksen üzerindeki gerçek azami değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Eksenin gerçek küçük birimini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Eksen üzerindeki gerçek asgari değeri belirtir. Gerçek değeri almak için önceden IChart.ValidateChartLayout() metodunu çağırın. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Kategori ekseninin (binleme) toplama türünü temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almaya izin verir. Yalnızca okunabilir [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Değer ekseninin kategoriler arasında kategori eksenini kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-D grafiklerde uygulanmaz. Okunabilir/Yazılabilir Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Kategori ekseninin türünü belirtir. Okunabilir/Yazılabilir [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Eksenin, dik eksenin onun üzerine kesildiği noktayı temsil eder. Okunabilir/Yazılabilir Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Diğer eksenin kesildiği belirtilen eksende CrossType'ı temsil eder. Okunabilir/Yazılabilir [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir. Okunabilir/Yazılabilir [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Eksenin biçimini temsil eder. Yalnızca okunabilir [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bir eksenin görünür başlığı olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Azami değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Asgari değerin otomatik olarak atanıp atanmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Otomatik taşma bin değerini belirtir. Yanlış ise: OverflowBin özelliğini kullanın. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Otomatik işaret etiketi aralığı değerini belirtir. Yanlış ise: TickLabelSpacing özelliğini kullanın. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Otomatik işaretçik aralığı değerini belirtir. Yanlış ise: TickMarksSpacing özelliğini kullanın. Okunabilir/Yazılabilir Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Otomatik eksik bin değerini belirtir. Yanlış ise: UnderflowBin özelliğini kullanın. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Değer ekseninin ölçek türünün logaritmik olup olmadığını temsil eder. Okunabilir/Yazılabilir Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Biçimin bağlı kaynak verisi olup olmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Taşma bin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | MS PowerPoint'in veri noktalarını sonuncudan birincisine sıralayıp sıralamadığını temsil eder. Okunabilir/Yazılabilir Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Eksik bin uygulanıp uygulanmadığını belirtir. Eksik bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Eksenin görünür olup olmadığını temsil eder. Okunabilir/Yazılabilir Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunabilir/Yazılabilir UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunabilir/Yazılabilir Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Grafik eksenindeki büyük ızgara çizgileri biçimini temsil eder. Yalnızca okunabilir [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Belirtilen eksen için büyük işaret çubuğu türünü temsil eder. Okunabilir/Yazılabilir [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Tarih veya değer ekseni için büyük birimleri temsil eder. Okunabilir/Yazılabilir Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Tarih ekseni için büyük birim ölçeğini temsil eder. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Değer eksenindeki azami değeri temsil eder. Okunabilir/Yazılabilir Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder. Yalnızca okunabilir [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Belirtilen eksen için küçük işaret çubuğu türünü temsil eder. Okunabilir/Yazılabilir [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Tarih veya değer ekseni için küçük birimleri temsil eder. Okunabilir/Yazılabilir Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Tarih ekseni için büyük birim ölçeğini temsil eder. Okunabilir/Yazılabilir [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Değer eksenindeki asgari değeri temsil eder. Okunabilir/Yazılabilir Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Eksen Etiketleri için biçim dizesini temsil eder. Okunabilir/Yazılabilir String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Taşma bin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Eksen konumunu temsil eder. Okunabilir/Yazılabilir [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Büyük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Yalnızca okunabilir Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Küçük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. Yalnızca okunabilir Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Belirtilen eksende işaret çubuğu etiketlerinin konumunu temsil eder. Okunabilir/Yazılabilir [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | İşaret etiketlerinin döndürme açısını temsil eder. Okunabilir/Yazılabilir Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Çizilen etiketler arasında kaç işaret etiketi atlanacağını belirtir. Okunabilir/Yazılabilir UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Bir sonraki işaret çubuğu çizilmeden önce kaç işaret çubuğunun atlanacağını belirtir. Kategori veya seri eksenine uygulanır. Okunabilir/Yazılabilir UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Eksenin başlığını alır. Yalnızca okunabilir [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Eksik bin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Eksen verilerine göre otomatik olarak belirlenen bir değerle IAxis.CategoryAxisType özelliğini ayarlar. |

### Ayrıca bakınız

* arayüz [IFormattedTextContainer](../iformattedtextcontainer)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->