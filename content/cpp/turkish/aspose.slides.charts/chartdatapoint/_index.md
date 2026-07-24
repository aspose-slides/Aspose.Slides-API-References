---
title: ChartDataPoint
second_title: Aspose.Slides for C++ API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 144
url: /tr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint sınıfı

Seri veri noktasını temsil eder.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğine göre nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında başvuru türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Şema öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Şema öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualX](./get_actualx/)() override | Şema öğesinin üst sol köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualY](./get_actualy/)() override | Şema öğesinin üst sol köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize. Yalnızca okuma [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | Şema veri noktasının renk değerini döndürür. Harita şemalarında kullanılır. Yalnızca okuma [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | Belirtilen indekste bir veri noktası seviyesini döndürür. Treeamp ve Sunburst serileri uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | Veri noktası seviyelerinin konteynerini döndürür. Treeamp ve Sunburst serileri uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Yalnızca okuma [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| **int32_t** [get_Explosion](./get_explosion/)() override | Veri noktasının pasta merkezinden ne kadar hareket edeceğini belirtir. **int32_t** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Biçimlendirme özelliklerini temsil eder. [IFormat](../iformat/) okunur. |
| **uint32_t** [get_Index](./get_index/)() override | Bu veri noktasının ebeveynin çocuk koleksiyonlarından hangisine uygulandığını belirler. **uint32_t** okunur. |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. **bool** okunur. |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | Baloncukların 3B etkisine sahip olduğunu belirtir. **bool** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | Etiket. Yalnızca okuma [IDataLabel](../idatalabel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | Bir veri işaretleyiciyi belirtir. Yalnızca okuma [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Bu listedeki şema tipi durumunda ilgili lejand girişinin özellikleri: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Yalnızca okuma [ILegendEntryProperties](../ilegendentryproperties/). |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi tipi için uygulanır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | Şema veri noktasının boyut değerini döndürür. Treemap ve Sunburst şemalarında kullanılır. Yalnızca okuma [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | Değer. Yalnızca okuma [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue. Yalnızca okuma [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue. Yalnızca okuma [IDoubleChartValue](../idoublechartvalue/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve şema stiline dayalı olarak veri noktasının otomatik rengini döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogu. Özel nesnelerin karma oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirmesi. |
| void [Remove](./remove/)() override | DataPoint'i şema serilerinden kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | Veri noktasının pasta merkezinden ne kadar hareket edeceğini belirtir. **int32_t** yazar. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Biçimlendirme özelliklerini temsil eder. [IFormat](../iformat/) yazar. |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. **bool** yazar. |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | Baloncukların 3B etkisine sahip olduğunu belirtir. **bool** yazar. |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi tipi için uygulanır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Konteynerlerdeki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IChartDataPoint](../ichartdatapoint/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)