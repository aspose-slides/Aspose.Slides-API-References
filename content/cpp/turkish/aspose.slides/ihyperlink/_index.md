---
title: IHyperlink
second_title: Aspose.Slides için C++ API Referansı
description: Bir hyperlink'i temsil eder.
type: docs
weight: 2523
url: /tr/aspose.slides/ihyperlink/
---
## IHyperlink sınıfı

Bir hiperlinki temsil eder.

```cpp
class IHyperlink : public virtual System::Object
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı halde, C#-stili kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı halde, C#-stili kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | HyperLinkEx'in eylem türünü döndürür. Yalnızca okunabilir [HyperlinkActionType](../hyperlinkactiontype/). |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | Hyperlink renginin kaynağını temsil eder - ya stiller ya da bölüm biçimi. Okunur [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | Harici URL'i belirtir. Bu özellik null olmaktan çıkarsa TargetSlide özelliği null olur. Yalnızca okunabilir [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | Bu bölümün gerçek içeriğine bakılmaksızın bu bölüm için ayarlanmış bir hyperlink'i temsil eder. |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | Tıklamada hyperlink'in vurgulanıp vurgulanmayacağını belirler. Okunur **bool**. |
| virtual **bool** [get_History](./get_history/)() | Üst hyperlink'in hedefinin, çağrıldığında görüntülenen hyperlink'ler listesine eklenip eklenmeyeceğini belirler. Okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Hyperlink'in çalan sesini temsil eder. Okunur [IAudio](../iaudio/). |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | Hyperlink tıklandığında sesin durdurulup durdurulmayacağını belirler. Okunur **bool**. |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | Üst hyperlink'in hedefi için, mevcut olduğunda, üst HTML çerçeve seti içinde çerçeveyi döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | HyperlinkEx belirli bir slaytı hedefliyorsa bu slaytı döndürür. Özellik null olmaktan çıkarsa ExternalUrl özelliği null olur. Yalnızca okunabilir [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | Üst hyperlink ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Okunur [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | Hyperlink renginin kaynağını temsil eder - ya stiller ya da bölüm biçimi. Yaz [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | Tıklamada hyperlink'in vurgulanıp vurgulanmayacağını belirler. Yaz **bool**. |
| virtual void [set_History](./set_history/)(**bool**) | Üst hyperlink'in hedefinin, çağrıldığında görüntülenen hyperlink'ler listesine eklenip eklenmeyeceğini belirler. Yaz **bool**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Hyperlink'in çalan sesini temsil eder. Yaz [IAudio](../iaudio/). |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | Hyperlink tıklandığında sesin durdurulup durdurulmayacağını belirler. Yaz **bool**. |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | Üst hyperlink'in hedefi için, mevcut olduğunda, üst HTML çerçeve seti içinde çerçeveyi döndürür. Yaz [System::String](../../system/string/). |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | Üst hyperlink ile ilişkili olarak kullanıcı arayüzünde gösterilebilecek dizeyi döndürür. Yaz [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalı. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalı. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalı. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)