---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides için C++ API Referansı
description: Sunumun tüm alt bilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
weight: 3407
url: /tr/aspose.slides/ipresentationheaderfootermanager/
---
## IPresentationHeaderFooterManager sınıf

Sunumun tüm alt bilgi, tarih-saat ve sayfa numarası yer tutucularının davranışını tutan yöneticiyi temsil eder.

```cpp
class IPresentationHeaderFooterManager : public virtual Aspose::Slides::IBaseHeaderFooterManager
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-style double kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string ve nullptr durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumudur. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumudur. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) | Ana slaytlar, yerleşim slaytları ve slaytlar dahil olmak üzere tüm tarih-saat yer tutucularına metin ayarlar. |
| virtual void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) | Ana slaytlar, yerleşim slaytları ve slaytlar dahil olmak üzere tüm tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| virtual void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) | Ana slaytlar, yerleşim slaytları ve slaytlar dahil olmak üzere tüm alt bilgi yer tutucularına metin ayarlar. |
| virtual void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) | Ana slaytlar, yerleşim slaytları ve slaytlar dahil olmak üzere tüm alt bilgi yer tutucularının görünürlüğünü değiştirir. |
| virtual void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) | Notlar ana, not slaytları ve el ilanı ana dahil olmak üzere tüm üst bilgi yer tutucularına metin ayarlar. |
| virtual void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) | Notlar ana, not slaytları ve el ilanı ana dahil olmak üzere tüm üst bilgi yer tutucularının görünürlüğünü değiştirir. |
| virtual void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) | Ana slaytlar, yerleşim slaytları ve slaytlar dahil olmak üzere tüm sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| virtual void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) | Tüm başlık slaytları ve ilk yerleşim slaytı için alt bilgi, tarih-saat ve sayfa numarası yer tutucularının görünürlüğünü değiştirir. Başlık slaytları \\u2013 ilk yerleşim slaytına dayalı slaytlardır (bu ilk yerleşimin tipine bakılmaksızın). |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını gerçekleştirir. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBaseHeaderFooterManager](../ibaseheaderfootermanager/)
* İsim uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)