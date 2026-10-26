---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides için C++ API Referansı
description: Sunumdaki tüm altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
weight: 4863
url: /tr/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager sınıf

Sunumda bulunan tüm altbilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN herhangi bir değere (NaN dahil) eşit değildir, ancak iki NaN eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN herhangi bir değere (NaN dahil) eşit değildir, ancak iki NaN eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | Ana slaytlar, düzen slaytları, slaytlar, notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm tarih-saat yer tutucularına metin ayarlar. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | Ana slaytlar, düzen slaytları, slaytlar, notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | Ana slaytlar, düzen slaytları, slaytlar, notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm altbilgi yer tutucularına metin ayarlar. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | Ana slaytlar, düzen slaytları, slaytlar, notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm altbilgi yer tutucularının görünürlüğünü değiştirir. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | Notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm üstbilgi yer tutucularına metin ayarlar. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | Notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm üstbilgi yer tutucularının görünürlüğünü değiştirir. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | Ana slaytlar, düzen slaytları, slaytlar, notlar ana slaytı, not slaytları ve el ilanı ana slaytı dahil olmak üzere tüm sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | Tüm başlık slaytları ve ilk düzen slaytı için altbilgi, tarih-saat ve sayfa numarası yer tutucularının görünürlüğünü değiştirir. Başlık slaytları – ilk düzen slaytına dayalı slaytlar (bu ilk düzenin tipinden bağımsız). |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseHeaderFooterManager](../baseheaderfootermanager/)
* Sınıf [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* İsim Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)