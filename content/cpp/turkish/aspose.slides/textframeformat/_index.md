---
title: TextFrameFormat
second_title: Aspose.Slides for C++ API Referansı
description: TextFrame'in formatTextFrameFormatting özelliklerini içerir.
type: docs
weight: 5461
url: /tr/aspose.slides/textframeformat/
---
## TextFrameFormat sınıfı

[TextFrame](../textframe/)'nin formatTextFrameFormatting özelliklerini içerir.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesne ile karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını (IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmaması gerektiğine rağmen) taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını (IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmaması gerektiğine rağmen) taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Bir [TextFrame](../textframe/) içinde dikey çapa metnini döndürür. [TextAnchorType](../textanchortype/) okuyun. |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Metnin otomatik sığdırma modunu döndürür. [TextAutofitType](../textautofittype/) okuyun. |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | [NullableBool::True](../nullablebool/) ise metin kutunun içinde yatay olarak ortalanmalıdır. [NullableBool](../nullablebool/) okuyun. |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Metin alanındaki sütun sayısını döndürür. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. 0 değeri tanımsız anlamına gelir. **int32_t** okuyun. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Metin alanındaki sütunlar arasındaki boşluğu (puant) döndürür. Bu, birden fazla sütun olduğunda uygulanmalıdır. Değer pozitif olmalıdır; aksi takdirde sıfıra ayarlanır. **double** okuyun. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | 3D Döndürme efekti uygulanmış olsa bile metnin düz kalmasını alır. **bool** okuyun. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | [TextFrame](../textframe/) içinde alt kenar boşluğunu (puant) döndürür. **double** okuyun. |
| **double** [get_MarginLeft](./get_marginleft/)() override | [TextFrame](../textframe/) içinde sol kenar boşluğunu (puant) döndürür. **double** okuyun. |
| **double** [get_MarginRight](./get_marginright/)() override | [TextFrame](../textframe/) içinde sağ kenar boşluğunu (puant) döndürür. **double** okuyun. |
| **double** [get_MarginTop](./get_margintop/)() override | [TextFrame](../textframe/) içinde üst kenar boşluğunu (puant) döndürür. **double** okuyun. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Salt-okunur [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. Salt-okunur [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Kutu içinde metne uygulanan özel dönüşümü belirler. Belirtilmezse, ekli şeklin dönüşümü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şeklin dönüşümü metnin dönüşümüne ek olarak uygulanabilir. Görsel metin dönüşümünün bu özelliğinden ve TextVerticalType özelliğindeki önceden tanımlı dikey tipten özetlenen sonucu. **float** okuyun. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Metin yönelimini belirler. Görsel metin dönüşümünün bu özelliğinden ve RotationAngle özelliğindeki özel açıdan özetlenen sonucu. [Slides::TextVerticalType](../textverticaltype/) okuyun. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Metin için 3B efekt özelliklerini temsil eden [ThreeDFormat](../threedformat/) nesnesini döndürür. Salt-okunur [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Metin kaydırma şeklini alır. [TextShapeType](../textshapetype/) okuyun. |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | [TextFrame](../textframe/) kenar boşluklarında metin kaydırılırsa **True** döner. [NullableBool](../nullablebool/) okuyun. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Uygulanan kalıtımla etkili metin çerçevesi biçimlendirme verilerini alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel türlerin kopyalanmasını etkinleştirir. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesne başlatır ve alt sınıfların kopya yapılandırmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesne başlatır ve alt sınıfların kopya yapılandırmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize ve nullptr durumuna özgü bir özelleştirmedir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize durumuna özgü bir özelleştirmedir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | [TextFrame](../textframe/) içinde dikey çapa metnini ayarlar. [TextAnchorType](../textanchortype/) yazın. |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Metnin otomatik sığdırma modunu ayarlar. [TextAutofitType](../textautofittype/) yazın. |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | [NullableBool::True](../nullablebool/) ise metin kutunun içinde yatay olarak ortalanmalıdır. [NullableBool](../nullablebool/) yazın. |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Metin alanındaki sütun sayısını ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. 0 değeri tanımsızdır. **int32_t** yazın. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Metin alanındaki sütunlar arasındaki boşluğu (puant) ayarlar. Bu, birden fazla sütun olduğunda uygulanmalıdır. Değer pozitif olmalıdır; aksi takdirde sıfıra ayarlanır. **double** yazın. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | 3D Döndürme efekti uygulanmış olsa bile metnin düz kalmasını ayarlar. **bool** yazın. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/) içinde alt kenar boşluğunu (puant) ayarlar. **double** yazın. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/) içinde sol kenar boşluğunu (puant) ayarlar. **double** yazın. |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/) içinde sağ kenar boşluğunu (puant) ayarlar. **double** yazın. |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/) içinde üst kenar boşluğunu (puant) ayarlar. **double** yazın. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Kutu içinde metne uygulanan özel dönüşümü belirler. Belirtilmezse, ekli şeklin dönüşümü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şeklin dönüşümü metnin dönüşümüne ek olarak uygulanabilir. Görsel metin dönüşümünün bu özelliğinden ve TextVerticalType özelliğindeki önceden tanımlı dikey tipten özetlenen sonucu. **float** yazın. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Metin yönelimini belirler. Görsel metin dönüşümünün bu özelliğinden ve RotationAngle özelliğindeki özel açıdan özetlenen sonucu. [Slides::TextVerticalType](../textverticaltype/) yazın. |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Metin kaydırma şeklini ayarlar. [TextShapeType](../textshapetype/) yazın. |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | [TextFrame](../textframe/) kenar boşluklarında metin kaydırılıyorsa **True** döner. [NullableBool](../nullablebool/) yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [TextFrameFormat](./textframeformat/)() | [TextFrameFormat](./) sınıfının yeni bir örneğini başlatır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [PVIObject](../pviobject/)
* Sınıf [ITextFrameFormat](../itextframeformat/)
* Sınıf [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)