---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
weight: 391
url: /tr/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat sınıf

[DataLabel](../datalabel/) için biçimlendirme seçeneklerini temsil eder.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Grafiği döndürür. Salt-okunur [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Veri etiketinin formatını temsil eder. Salt-okunur [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Oku **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | DataLabels nesnesi için format dizesini temsil eder. Oku [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Salt-okunur [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) nesnesini döndürür. Salt-okunur [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Veri etiketinin konumunu temsil eder. Oku [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Bir grafikte veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. Oku [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Belirtilen grafiğin veri etiketi balon boyutu değerinin gösterim davranışını temsil eder. True ise balon boyutu değerini gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Belirtilen grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True ise grafikte veri etiketlerinin kategori adını gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Belirtilen grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Belirtilen grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. True ise hücre değerini gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Belirtilen grafiğin veri etiketi lider çizgileri gösterim davranışını temsil eder. True ise lider çizgilerini gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Belirtilen grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. True ise veri etiketi lejand anahtarı görünür. Oku **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Grafikte veri etiketleri için serinin adının gösterim davranışını belirten bir Boolean döndürür. True ise seri adını gösterir. False ise gizler. Oku **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Grafik metin formatını döndürür. Salt-okunur [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Karma kodu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemeyi uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumu için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Yaz **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | DataLabels nesnesi için format dizesini temsil eder. Yaz [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Veri etiketinin konumunu temsil eder. Yaz [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Bir grafikte veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. Yaz [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Belirtilen grafiğin veri etiketi balon boyutu değerinin gösterim davranışını temsil eder. True ise balon boyutu değerini gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Belirtilen grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True ise grafikte veri etiketlerinin kategori adını gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Belirtilen grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Belirtilen grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. True ise hücre değerini gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Belirtilen grafiğin veri etiketi lider çizgileri gösterim davranışını temsil eder. True ise lider çizgilerini gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Belirtilen grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. True ise veri etiketi lejand anahtarı görünür. Yaz **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Grafikte veri etiketleri için serinin adının gösterim davranışını belirten bir Boolean ayarlar. True ise seri adını gösterir. False ise gizler. Yaz **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Belirtilen grafiğin veri etiketi yüzde değeri gösterim davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidi açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [PVIObject](../../aspose.slides/pviobject/)
* Sınıf [IDataLabelFormat](../idatalabelformat/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)