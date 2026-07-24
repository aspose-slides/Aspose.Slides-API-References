---
title: BoxedValue< ValueTuple< Args... > >
second_title: Aspose.Slides for C++ API Referansı
description: Değer demetinin kutulanmış sürümü.
type: docs
weight: 118
url: /tr/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > sınıf


Değer demetinin kutulanmış sürümü.

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| name | Args demet öğesi türleri. |
## Yöntemler

| Metot | Açıklama |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | Belirtilen değeri kutulmuş olarak temsil eden bir [BoxedValue](../boxedvalue/) nesnesi oluşturur. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Geçerli ve belirtilen nesneler tarafından temsil edilen kutulanmış değerlerin eşitliğini belirler. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# stilinde karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerlere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerlere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| int [GetHashCode](./gethashcode/)() const override | Geçerli nesne için bir karma kod döndürür. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek tipini alır. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | index konumundaki öğeyi döndürür. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneğini temsil edip etmediğini denetler. C# 'is' operatörünün benzeri. |
| **bool** [is](./is/)() const | Geçerli nesne tarafından temsil edilen kutulanmış değerin tipinin **V** olup olmadığını belirler. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun C# benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nın dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'ın dize durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kaplarda işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| [String](../string/) [ToString](./tostring/)() const override | Kutulanmış değerin dize temsilini döndürür. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | Kutulanmış değerin paketini açar. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca bakınız

* Sınıf [ITuple](../../system.runtime.compilerservices/ituple/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)