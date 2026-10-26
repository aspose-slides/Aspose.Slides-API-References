---
title: IChartSeriesGroup
second_title: C++ için Aspose.Slides API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 846
url: /tr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup sınıfı

Seri grubunu temsil eder.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği hâlde eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği hâlde eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Balon grafikinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okuma [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. Sadece okuma [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Belirtilen indeksdeki gruptaki grafik serisini döndürür. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Halka grafikindeki deliğin boyutunu belirtir (çizim alanının %10 ile %90 arasında olabilir). Okuma **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | İlk pasta veya halka grafik diliminin açısını derece cinsinden alır (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okuma **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür. Okuma **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Okuma **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Grafik seri çizgileri varsa doğrudur. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okuma **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Pie-of-pie veya bar-of-pie grafiklerinde hangi veri noktalarının ikinci pasta veya çubukta olduğunu belirleme şekli. Okuma [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Özel bölme bilgisiyle bir pie-of-pie veya bar-of-pie grafik için. İndeks ile ikinci pasta veya çubukta çizilecek veri noktasını döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Özel bölme bilgisiyle bir pie-of-pie veya bar-of-pie grafik için. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Sadece okuma [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okuma **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Bu grubun serisinin ikincil eksende çizilip çizilmediğini gösterir. Sadece okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Sadece okuma [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta veya çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir ( %5 ile %200 arasında olabilir). Okuma **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Grafik serilerinin yalnızca okunabilir bir koleksiyonunu döndürür. Sadece okuma [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Sadece okuma [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Bu seri grubunun tipini döndürür. Sadece okuma [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Çizgi veya Hisse grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Sadece okuma [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Belirtilen indeksteki öğeyi alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Yaz [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Yaz **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Halka grafiğinde deliğin boyutunu belirtir (çizim alanının %10 ile %90 arasında). Yaz **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | İlk pasta veya halka grafik diliminin açısını derece cinsinden ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Yaz **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak ayarlar. Yaz **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Yaz **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Grafik seri çizgileri varsa doğrudur. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Yaz **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Yaz **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Pie-of-pie veya bar-of-pie grafiklerinde hangi veri noktalarının ikinci pasta veya çubukta olduğunu belirleme şeklini belirtir. Yaz [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Yaz **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta veya çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir ( %5 ile %200 arasında). Yaz **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumı için özet ve açıklamalara bakınız. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). [ChartSeriesGroup](../chartseriesgroup/) sınıfındaki "seri grup özellikleri" okuma/yazmadır. "seri grup özellikleri"nin her biri [ChartSeries](../chartseries/) sınıfında yalnızca okuma olarak sunulabilir.

## Ayrıca Bakınız

* Sınıf [IChartComponent](../ichartcomponent/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)