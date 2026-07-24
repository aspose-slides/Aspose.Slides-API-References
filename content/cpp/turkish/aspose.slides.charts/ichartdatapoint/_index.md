---
title: IChartDataPoint
second_title: Aspose.Slides için C++ API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 677
url: /tr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint sınıf

Seri veri noktasını temsil eder.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Grafik veri noktasının balon boyutunu döndürür. Yalnızca okunur [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Yalnızca okunur [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Belirtilen dizindeki veri noktası seviyesini döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Veri noktası seviyelerinin konteynerini döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | Özel değer tipinde seri hata çubukları değerlerini temsil eder. Yalnızca okunur [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Verinin pasta merkezinden ne kadar hareket edeceğini belirtir. **int32_t** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Biçimlendirme özelliklerini temsil eder. Okunur [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Bu veri noktasının geçerli olduğu ebeveynin çocuk koleksiyonunu belirler. **uint32_t** okunur. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. **bool** okunur. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Balonların 3B etkisi olduğunu belirtir. **bool** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | Grafik veri noktasının etiketini temsil eder. Yalnızca okunur [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Veri işaretçisini belirtir. Yalnızca okunur [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Belirtilen grafik türlerinde ilgili lejand girişi özelliklerini temsil eder: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Yalnızca okunur [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi türü için uygulanır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Yalnızca okunur [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Grafik veri noktasının değerini döndürür. Yalnızca okunur [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Grafik veri noktasının x değerini döndürür. Yalnızca okunur [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Grafik veri noktasının y değerini döndürür. Yalnızca okunur [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik rengini döndürür. FillType NotDefined ise bu renk varsayılan olarak kullanılır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType ile tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| virtual void [Remove](./remove/)() | Veri Noktasını grafik serisinden kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Verinin pasta merkezinden ne kadar hareket edeceğini belirtir. **int32_t** yazılır. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Biçimlendirme özelliklerini temsil eder. [IFormat](../iformat/) yazılır. |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. **bool** yazılır. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Balonların 3B etkisi olduğunu belirtir. **bool** yazılır. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi türü için uygulanır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Konteynerlerdeki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IActualLayout](../iactuallayout/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)