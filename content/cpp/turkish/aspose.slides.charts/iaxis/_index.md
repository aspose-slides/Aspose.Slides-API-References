---
title: IAxis
second_title: Aspose.Slides for C++ API Referansı
description: Grafik eksenini temsil eden nesneyi kapsüller.
type: docs
weight: 534
url: /tr/aspose.slides.charts/iaxis/
---
## IAxis sınıfı

Grafik eksenini temsil eden nesneyi kapsüller.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Eksenin gerçek ana birimini belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Eksenin gerçek ana birim ölçeğini belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Eksenin gerçek küçük birimini belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için daha önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Kategori ekseninin toplama türünü (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Değer ekseninin kategoriler arasındaki kategori eksenini kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklerde geçerli değildir. **bool** okunur. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. [TimeUnitType](../timeunittype/) okunur. |
| virtual **double** [get_BinWidth](./get_binwidth/)() | AggregationType özelliği [AxisAggregationType::ByBinWidth](../axisaggregationtype/) olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Kategori ekseninin tipini belirtir. [CategoryAxisType](../categoryaxistype/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. [IChart](../ichart/) salt okunurdur. |
| virtual **float** [get_CrossAt](./get_crossat/)() | Dik eksenin kesiştiği eksen üzerindeki noktayı temsil eder. **float** okunur. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. [CrossesType](../crossestype/) okunur. |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Değer ekseni için görüntüleme birimlerinin ölçekleme değerini belirtir. [DisplayUnitType](../displayunittype/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Eksen biçimini temsil eder. [IAxisFormat](../iaxisformat/) salt okunurdur. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Bir eksenin görünür başlığa sahip olup olmadığını belirler. **bool** okunur. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. **bool** okunur. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. **bool** okunur. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. **bool** okunur. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. **bool** okunur. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Otomatik taşma bin değeri belirtilir. false ise: OverflowBin özelliği kullanılır. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Otomatik tik etiketi aralığı değeri belirtilir. false ise: TickLabelSpacing özelliği kullanılır. **bool** okunur. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Otomatik tik işareti aralığı değeri belirtilir. false ise: TickMarksSpacing özelliği kullanılır. **bool** okunur. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Otomatik alt akış bin değeri belirtilir. false ise: UnderflowBin özelliği kullanılır. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. **bool** okunur. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Biçimin bağlanmış kaynak veri olup olmadığını gösterir. **bool** okunur. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | MS PowerPoint'in veri noktalarını sondan başa doğru çizer olup olmadığını temsil eder. **bool** okunur. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Alt akış bininin uygulanıp uygulanmadığını belirtir. Alt akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Eksenin görünür olup olmadığını temsil eder. **bool** okunur. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Etiklerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. **uint16_t** okunur. |
| virtual **double** [get_LogBase](./get_logbase/)() | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. **double** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Grafik eksenindeki ana ızgara çizgileri biçimini temsil eder. [IChartLinesFormat](../ichartlinesformat/) salt okunurdur. |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Belirtilen eksen için ana tik işareti tipini temsil eder. [TickMarkType](../tickmarktype/) okunur. |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Tarih veya değer ekseni için ana birimleri temsil eder. **double** okunur. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Tarih ekseni için ana birim ölçeğini temsil eder. [TimeUnitType](../timeunittype/) okunur. |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Değer eksenindeki maksimum değeri temsil eder. **double** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder. [IChartLinesFormat](../ichartlinesformat/) salt okunurdur. |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Belirtilen eksen için küçük tik işareti tipini temsil eder. [TickMarkType](../tickmarktype/) okunur. |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Tarih veya değer ekseni için küçük birimleri temsil eder. **double** okunur. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Tarih ekseni için ana birim ölçeğini temsil eder. [TimeUnitType](../timeunittype/) okunur. |
| virtual **double** [get_MinValue](./get_minvalue/)() | Değer eksenindeki minimum değeri temsil eder. **double** okunur. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | [Axis](../axis/) Etiketleri için biçim dizesini temsil eder. [System::String](../../system/string/) okunur. |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | AggregationType özelliği [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Taşma bin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Eksen konumunu temsil eder. [AxisPositionType](../axispositiontype/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. [IPresentation](../../aspose.slides/ipresentation/) salt okunurdur. |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Ana ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. **bool** salt okunurdur. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Küçük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder. **bool** salt okunurdur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. [IBaseSlide](../../aspose.slides/ibaseslide/) salt okunurdur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Grafik metin biçimini döndürür. [IChartTextFormat](../icharttextformat/) salt okunurdur. |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Belirtilen eksende tik işareti etiketlerinin konumunu temsil eder. [TickLabelPositionType](../ticklabelpositiontype/) okunur. |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Tik etiketlerinin dönme açısını temsil eder. **float** okunur. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Çizilen etiketler arasında atlanacak tik etiketi sayısını belirtir. **uint32_t** okunur. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Bir sonraki işarete gelmeden önce atlanacak tik işareti sayısını belirtir. Kategori veya seri eksenine uygulanır. **uint16_t** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Eksen başlığını alır. [IChartTitle](../icharttitle/) salt okunurdur. |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Alt akış bin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türe ait bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Kategori ekseninin toplama türünü (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Değer ekseninin kategoriler arasındaki kategori eksenini kesip kesmediğini temsil eder. Bu özellik yalnızca kategori eksenlerine uygulanır ve 3D grafiklerde geçerli değildir. **bool** yazılır. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir. [TimeUnitType](../timeunittype/) yazılır. |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | AggregationType özelliği [AxisAggregationType::ByBinWidth](../axisaggregationtype/) olarak ayarlandığında bin genişliğini belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Kategori ekseninin tipini belirtir. [CategoryAxisType](../categoryaxistype/) yazılır. |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Dik eksenin kesiştiği eksen üzerindeki noktayı temsil eder. **float** yazılır. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Diğer eksenin kesiştiği belirtilen eksende CrossType'ı temsil eder. [CrossesType](../crossestype/) yazılır. |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Değer ekseni için görüntüleme birimlerinin ölçekleme değerini belirtir. [DisplayUnitType](../displayunittype/) yazılır. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Bir eksenin görünür başlığı olup olmadığını belirler. **bool** yazılır. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Eksenin ana biriminin otomatik olarak atanıp atanmadığını gösterir. **bool** yazılır. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir. **bool** yazılır. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir. **bool** yazılır. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir. **bool** yazılır. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Otomatik taşma bin değeri belirtilir. false ise: OverflowBin özelliği kullanılır. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Otomatik tik etiketi aralığı değeri belirtilir. false ise: TickLabelSpacing özelliği kullanılır. **bool** yazılır. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Otomatik tik işareti aralığı değeri belirtilir. false ise: TickMarksSpacing özelliği kullanılır. **bool** yazılır. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Otomatik alt akış bin değeri belirtilir. false ise: UnderflowBin özelliği kullanılır. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder. **bool** yazılır. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Biçimin bağlanmış kaynak veri olup olmadığını gösterir. **bool** yazılır. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | MS PowerPoint'in veri noktalarını sondan başa doğru çizer olup olmadığını temsil eder. **bool** yazılır. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Alt akış bininin uygulanıp uygulanmadığını belirtir. Alt akış bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Eksenin görünür olup olmadığını temsil eder. **bool** yazılır. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Etiklerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır. **uint16_t** yazılır. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur. **double** yazılır. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Belirtilen eksen için ana tik işareti tipini temsil eder. [TickMarkType](../tickmarktype/) yazılır. |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Tarih veya değer ekseni için ana birimleri temsil eder. **double** yazılır. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Tarih ekseni için ana birim ölçeğini temsil eder. [TimeUnitType](../timeunittype/) yazılır. |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Değer eksenindeki maksimum değeri temsil eder. **double** yazılır. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Belirtilen eksen için küçük tik işareti tipini temsil eder. [TickMarkType](../tickmarktype/) yazılır. |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Tarih veya değer ekseni için küçük birimleri temsil eder. **double** yazılır. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Tarih ekseni için ana birim ölçeğini temsil eder. [TimeUnitType](../timeunittype/) yazılır. |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Değer eksenindeki minimum değeri temsil eder. **double** yazılır. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | [Axis](../axis/) Etiketleri için biçim dizesini temsil eder. [System::String](../../system/string/) yazılır. |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | AggregationType özelliği [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) olarak ayarlandığında bin sayısını belirtir. Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Taşma bin özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Eksen konumunu temsil eder. [AxisPositionType](../axispositiontype/) yazılır. |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Belirtilen eksende tik işareti etiketlerinin konumunu temsil eder. [TickLabelPositionType](../ticklabelpositiontype/) yazılır. |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Tik etiketlerinin dönme açısını temsil eder. **float** yazılır. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Çizilen etiketler arasında atlanacak tik etiketi sayısını belirtir. **uint32_t** yazılır. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Bir sonraki işarete gelmeden önce atlanacak tik işareti sayısını belirtir. Kategori veya seri eksenine uygulanır. **uint16_t** yazılır. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Alt akış bin özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | IAxis::get(set)_CategoryAxisType özelliğini eksen verilerine dayanarak otomatik belirlenen bir değerle ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşılan değil) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Diğer

* Sınıf [IFormattedTextContainer](../iformattedtextcontainer/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)