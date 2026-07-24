---
title: IPoint
second_title: Aspose.Slides for C++ API Referansı
description: Animasyon noktasını temsil eder.
type: docs
weight: 313
url: /tr/aspose.slides.animation/ipoint/
---
## IPoint sınıf

Animasyon noktasını temsil eder.

```cpp
class IPoint : public virtual System::Object
```

## Methods

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamı kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'da NaN'ın herhangi bir değere, NaN dahil, eşit olmadığına rağmen, eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'da NaN'ın herhangi bir değere, NaN dahil, eşit olmadığına rağmen, eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | Değerler, from, to, by öznitelikleri içinde şu bileşenlerden oluşan formüller yapılabilir: Standart aritmetik operatörler: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) Sabitler: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD Koşullu operatörler: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometri operatörleri: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD Doğal logaritma \\uFFFDln()\\uFFFD Özellik referansları (host destekli özellikler) |
| virtual **float** [get_Time](./get_time/)() | Zaman değerini temsil eder. **float** okur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Nokta değerini temsil eder. Yalnızca: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. [System::Object](../../system/object/) okur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumunun string ve nullptr için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumunun stringler için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | Değerler, from, to, by öznitelikleri içinde şu bileşenlerden oluşan formüller yapılabilir: Standart aritmetik operatörler: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) Sabitler: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD Koşullu operatörler: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometri operatörleri: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD Doğal logaritma \\uFFFDln()\\uFFFD Özellik referansları (host destekli özellikler) |
| virtual void [set_Time](./set_time/)(**float**) | Zaman değerini temsil eder. **float** yazar. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Nokta değerini temsil eder. Yalnızca: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. [System::Object](../../system/object/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon bağımsız değişkeni zayıf gösterge (shared yerine) olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler ve ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* İsimUzayı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)