---
title: Axis
second_title: Aspose.Slides for C++ API Referansı
description: Bir grafiğin eksenini temsil eden nesneyi kapsül eder.
type: docs
weight: 14
url: /tr/aspose.slides.charts/axis/
---
## Axis sınıfı

Bir grafiğin eksenini temsil eden nesneyi kapsül eder.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Eksenin gerçek ana birimini belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Eksenin gerçek küçük birimini belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için önceden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Kategori ekseninin toplama türünü (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Değer ekseninin kategoriler arasındaki kategori eksenini kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklere uygulanmaz. Okunur **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Okunur [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | AggregationType özelliği [AxisAggregationType::ByBinWidth](../axisaggregationtype/) olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Kategori ekseninin türünü belirtir. Okunur [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Üst chart'ı döndürür. Yalnızca okuma [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Dikey eksenin ekseni kestiği noktayı temsil eder. Okunur **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Belirtilen eksende diğer eksenin kesiştiği CrossType'ı temsil eder. Okunur [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Değer ekseni için görüntü birimlerinin ölçek değerini belirtir. Okunur [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Eksenin biçimini temsil eder. Yalnızca okuma [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Bir eksenin görünür başlığı olup olmadığını belirler. Okunur **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Eksenin ana biriminin otomatik atanıp atanmadığını gösterir. Okunur **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Maksimum değerin otomatik atanıp atanmadığını gösterir. Okunur **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Eksenin küçük biriminin otomatik atanıp atanmadığını gösterir. Okunur **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Minimum değerin otomatik atanıp atanmadığını gösterir. Okunur **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Otomatik taşma bin değerini belirtir. False ise: OverflowBin özelliğini kullan. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Otomatik tik etiketi aralığı değerini belirtir. False ise: TickLabelSpacing özelliğini kullan. Okunur **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Otomatik tik işaretleri aralığı değerini belirtir. False ise: TickMarksSpacing özelliğini kullan. Okunur **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Otomatik eksik akış bin değerini belirtir. False ise: UnderflowBin özelliğini kullan. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. Okunur **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Biçimin bağlı kaynak verisi olup olmadığını gösterir. Okunur **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullan. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | MS PowerPoint'in veri noktalarını sonuncudan ilkine çizip çizmediğini temsil eder. Okunur **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Eksik akış bininin uygulanıp uygulanmadığını belirtir. Eksik akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullan. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Eksenin görünür olup olmadığını temsil eder. Okunur **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Etiketteki etiketlerin eksenden olan mesafesini belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Okunur **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Okunur **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Grafik eksenindeki ana ızgara çizgilerinin biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Belirtilen eksen için ana tik işaretinin türünü temsil eder. Okunur [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Tarih veya değer ekseni için ana birimleri temsil eder. Okunur **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Tarih ekseni için ana birim ölçeğini temsil eder. Okunur [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Değer eksenindeki maksimum değeri temsil eder. Okunur **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Grafik eksenindeki küçük ızgara çizgilerinin biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Belirtilen eksen için küçük tik işaretinin türünü temsil eder. Okunur [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Tarih veya değer ekseni için küçük birimleri temsil eder. Okunur **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Tarih ekseni için ana birim ölçeğini temsil eder. Okunur [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Değer eksenindeki minimum değeri temsil eder. Okunur **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | [Axis](./) Etiketleri için biçim dizesini temsil eder. Okunur [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | AggregationType özelliği [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Taşma bininin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin true olduğunda uygulanır. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Eksenin konumunu temsil eder. Okunur [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Ana ızgara çizgisini gizlemek için [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() değerini [FillType::NoFill](../../aspose.slides/filltype/) olarak ayarlayın. Yalnızca okuma **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Küçük ızgara çizgisini gizlemek için [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() değerini [FillType::NoFill](../../aspose.slides/filltype/) olarak ayarlayın. Yalnızca okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Metnin biçimini temsil eder. Yalnızca okuma [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Belirtilen eksen üzerindeki tik işareti etiketlerinin konumunu temsil eder. Okunur [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Tik etiketlerinin döndürme açısını temsil eder. Okunur **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Çizilen etiketler arasında atlanacak tik etiketi sayısını belirtir. Kategori veya seri eksenine uygulanır. Okunur **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Bir sonraki çizilmeden önce atlanacak tik işareti sayısını belirtir. Kategori veya seri eksenine uygulanır. Okunur **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Eksenin başlığını alır. Yalnızca okuma [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Eksik akış bininin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin true olduğunda uygulanır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Kategori ekseninin toplama türünü (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Değer ekseninin kategoriler arasındaki kategori eksenini kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklere uygulanmaz. Yaz **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. Yaz [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | AggregationType özelliği [AxisAggregationType::ByBinWidth](../axisaggregationtype/) olduğunda bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Kategori ekseninin tipini belirtir. Yaz [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Dikey eksenin ekseni kestiği noktayı temsil eder. Yaz **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Belirtilen eksende diğer eksenin kesiştiği CrossType'ı temsil eder. Yaz [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Değer ekseni için görüntü birimlerinin ölçek değerini belirtir. Yaz [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Bir eksenin görünür bir başlığı olup olmadığını belirler. Yaz **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Eksenin ana biriminin otomatik atanıp atanmadığını gösterir. Yaz **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Maksimum değerin otomatik atanıp atanmadığını gösterir. Yaz **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Eksenin küçük biriminin otomatik atanıp atanmadığını gösterir. Yaz **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Minimum değerin otomatik atanıp atanmadığını gösterir. Yaz **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Otomatik taşma bin değerini belirtir. False ise: OverflowBin özelliğini kullan. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Otomatik tik etiketi aralığı değerini belirtir. False ise: TickLabelSpacing özelliğini kullan. Yaz **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Otomatik tik işaretleri aralığı değerini belirtir. False ise: TickMarksSpacing özelliğini kullan. Yaz **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Otomatik eksik akış bin değerini belirtir. False ise: UnderflowBin özelliğini kullan. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. Yaz **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Biçimin bağlı kaynak verisi olup olmadığını gösterir. Yaz **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullan. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | MS PowerPoint'in veri noktalarını sonundan başına çizip çizmediğini temsil eder. Yaz **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Eksik akış bininin uygulanıp uygulanmadığını belirtir. Eksik akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullan. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Eksenin görünür olup olmadığını temsil eder. Yaz **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Etiketteki etiketlerin eksenden mesafesini belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. Yaz **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. Yaz **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Belirtilen eksen için ana tik işaretinin tipini temsil eder. Yaz [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Tarih veya değer ekseni için ana birimleri temsil eder. Yaz **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Tarih ekseni için ana birim ölçeğini temsil eder. Yaz [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Değer eksenindeki maksimum değeri temsil eder. Yaz **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Belirtilen eksen için küçük tik işaretinin tipini temsil eder. Yaz [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Tarih veya değer ekseni için küçük birimleri temsil eder. Yaz **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Tarih ekseni için ana birim ölçeğini temsil eder. Yaz [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Değer eksenindeki minimum değeri temsil eder. Yaz **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | [Axis](./) Etiketleri için biçim dizesini temsil eder. Yaz [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | AggregationType özelliği [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Taşma bininin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin true olduğunda uygulanır. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Eksenin konumunu temsil eder. Yaz [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Belirtilen eksen üzerindeki tik işareti etiketlerinin konumunu temsil eder. Yaz [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Tik etiketlerinin döndürme açısını temsil eder. Yaz **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Çizilen etiketler arasında atlanacak tik etiketi sayısını belirtir. Kategori veya seri eksenine uygulanır. Yaz **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Bir sonraki çizilmeden önce atlanacak tik işareti sayısını belirtir. Kategori veya seri eksenine uygulanır. Yaz **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Eksik akış bininin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin true olduğunda uygulanır. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | IAxis::get(set)_CategoryAxisType özelliğini eksen verilerine dayanarak otomatik belirlenen bir değerle ayarlar. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Konteynerlerdeki göstergeleri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |
## İlgili

* Sınıf [DomObject](../../aspose.slides/domobject/)
* Sınıf [IAxis](../iaxis/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)