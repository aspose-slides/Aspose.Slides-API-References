---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 300
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıfı


Seri grubunu temsil eder.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Oku [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Oku **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Üst grafiği döndürür. Salt okunur [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Belirtilen indeksteki gruptaki grafik serisini döndürür. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Halkalı grafikteki deliğin boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). Oku **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | İlk pasta veya halkalı grafik diliminin açısını derece cinsinden alır (yukarıdan saat yönünde, 0 ile 360 derece arası). Oku **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür. Oku **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar. Oku **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Grafikte seri çizgileri varsa doğru döner. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle uygulanır. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Oku **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100'den %100'e). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içerdiğini belirleme yöntemini belirtir. Oku [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Özel bölme bilgisiyle bir pie-of-pie veya bar-of-pie grafiği için özel bölme bilgisi. İndeksle ikinci pasta veya çubukta çizilecek veri noktasını döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Özel bölme bilgisiyle bir pie-of-pie veya bar-of-pie grafiği için özel bölme bilgisi. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt okunur [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Oku **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Salt okunur **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, birinci pastanın boyutuna yüzde olarak belirtir ( %5 ile %200 arasında ). Oku **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Seri koleksiyonunu döndürür. Salt okunur [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Bu seri grubunun tipini döndürür. Salt okunur [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt okunur [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Belirtilen indeksteki öğeyi alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumundaki özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumundaki özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Baloncuk grafikindeki baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) yaz. |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Baloncuk grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında). **int32_t** yaz. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Halkalı grafikteki deliğin boyutunu belirtir (çizim alanının %0 ile %90 arasında). **uint8_t** yaz. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | İlk pasta veya halkalı grafik diliminin açısını derece cinsinden ayarlar (yukarıdan saat yönünde, 0-360 derece). **uint16_t** yaz. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 3B grafikte veri serileri arasındaki mesafeyi işaretçi genişliğinin yüzde olarak ayarlar. **uint16_t** yaz. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak ayarlar. **uint16_t** yaz. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. **bool** yaz. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Serideki her veri işaretçisinin farklı renkli olmasını belirtir. **bool** yaz. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 - %100). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içerdiğini belirleme yöntemini belirtir. [PieSplitType](../piesplittype/) yaz. |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. **double** yaz. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, birinci pastanın boyutuna yüzde olarak belirtir ( %5 - %200 ). **uint16_t** yaz. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici olarak ayarlar (paylaşımlı değil). Kapsayıcılardaki göstericileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamalara bakın. 2) Seri grubu, gruptaki her seri için ortak bazı seri özelliklerini içerir ("seri grup özellikleri"). [ChartSeriesGroup](./) sınıfındaki "seri grup özellikleri" okunur/yazılır. "Seri grup özellikleri"nin her biri [ChartSeries](../chartseries/) sınıfında yalnızca okunabilir bir projeksiyona sahip olabilir. 

## İlgili

* Sınıf [IChartSeriesGroup](../ichartseriesgroup/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* İsim Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)