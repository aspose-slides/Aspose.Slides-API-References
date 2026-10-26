---
title: LineFormat
second_title: Aspose.Slides for C++ API Referansı
description: Bir satırın biçimini temsil eder.
type: docs
weight: 4382
url: /tr/aspose.slides/lineformat/
---
## LineFormat sınıfı

Bir satırın biçimini temsil eder.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | İki [LineFormat](./) örneğinin eşit olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | Satır hizalamasını döndürür. [LineAlignment](../linealignment/)'yi okuyun. |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | Satırın başlangıcındaki ok ucu uzunluğunu döndürür. [LineArrowheadLength](../linearrowheadlength/)'yi okuyun. |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | Satırın başlangıcındaki ok ucu stilini döndürür. [LineArrowheadStyle](../linearrowheadstyle/)'yi okuyun. |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | Satırın başlangıcındaki ok ucu genişliğini döndürür. [LineArrowheadWidth](../linearrowheadwidth/)'yi okuyun. |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | Satır kaplama stilini döndürür. [LineCapStyle](../linecapstyle/)'yi okuyun. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | Özel tire desenini döndürür. **float**[]'ı okuyun. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | Satır tire stilini döndürür. [LineDashStyle](../linedashstyle/)'yi okuyun. |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | Satırın sonundaki ok ucu uzunluğunu döndürür. [LineArrowheadLength](../linearrowheadlength/)'yi okuyun. |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | Satırın sonundaki ok ucu stilini döndürür. [LineArrowheadStyle](../linearrowheadstyle/)'yi okuyun. |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | Satırın sonundaki ok ucu genişliğini döndürür. [LineArrowheadWidth](../linearrowheadwidth/)'yi okuyun. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | Satırın dolgu biçimini döndürür. Yalnızca okunabilir [ILineFillFormat](../ilinefillformat/). |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | Satır biçimi tanımlı değilse (yeni oluşturulmuş, varsayılan) doğru döndürür. Yalnızca okunabilir **bool**. |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | Satırların birleşme stilini döndürür. [LineJoinStyle](../linejoinstyle/)'yi okuyun. |
| **float** [get_MiterLimit](./get_miterlimit/)() override | Satırın kiriş sınırlamasını döndürür. **float**'ı okuyun. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Üst_Anlık nesnesini döndürür. Yalnızca okunabilir [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/)'yi döndürür. Yalnızca okunabilir [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | Satırın taslak biçimini döndürür. Yalnızca okunabilir [ILineFillFormat](../ilinefillformat/). |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | Satır stilini döndürür. [LineStyle](../linestyle/)'yi okuyun. |
| **double** [get_Width](./get_width/)() override | Satırın genişliğini döndürür. **double**'ı okuyun. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | Kalıtım uygulanmış etkili satır biçimlendirme verisini alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Karma kodu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan türe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel türlerin kopyalanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | Satır hizalamasını ayarlar. [LineAlignment](../linealignment/)'i yazın. |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Satırın başlangıcındaki ok ucu uzunluğunu ayarlar. [LineArrowheadLength](../linearrowheadlength/)'i yazın. |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Satırın başlangıcındaki ok ucu stilini ayarlar. [LineArrowheadStyle](../linearrowheadstyle/)'i yazın. |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Satırın başlangıcındaki ok ucu genişliğini ayarlar. [LineArrowheadWidth](../linearrowheadwidth/)'yi yazın. |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | Satır kaplama stilini ayarlar. [LineCapStyle](../linecapstyle/)'i yazın. |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Özel tire desenini ayarlar. **float**[]'ı yazın. |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | Satır tire stilini ayarlar. [LineDashStyle](../linedashstyle/)'yi yazın. |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Satırın sonundaki ok ucu uzunluğunu ayarlar. [LineArrowheadLength](../linearrowheadlength/)'yı yazın. |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Satırın sonundaki ok ucu stilini ayarlar. [LineArrowheadStyle](../linearrowheadstyle/)'i yazın. |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Satırın sonundaki ok ucu genişliğini ayarlar. [LineArrowheadWidth](../linearrowheadwidth/)'yi yazın. |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | Satırların birleşme stilini ayarlar. [LineJoinStyle](../linejoinstyle/)'i yazın. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | Satırın köşe sınırlamasını ayarlar. **float**'ı yazın. |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | Satır stilini ayarlar. [LineStyle](../linestyle/)'yi yazın. |
| void [set_Width](./set_width/)(**double**) override | Satırın genişliğini ayarlar. **double**'ı yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [PVIObject](../pviobject/)
* Sınıf [ILineFormat](../ilineformat/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)