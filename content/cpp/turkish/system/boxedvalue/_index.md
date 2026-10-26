---
title: BoxedValue
second_title: Aspose.Slides for C++ API Referansı
description: "Kutu içine alınmış bir değeri temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate (ayrılmalıdır). Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 105
url: /tr/system/boxedvalue/
---
## BoxedValue sınıfı

Kutu içine alınmış bir değeri temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak allocate (ayrılmalıdır). Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Sınıf tarafından temsil edilen kutuya alınmış değerin türü |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | Belirtilen kutuya alınmış değeri temsil eden bir nesne oluşturur. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Mevcut ve belirtilen nesneler tarafından temsil edilen kutuya alınmış değerlerin eşitliğini belirler. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# stilinde karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| int [GetHashCode](./gethashcode/)() const override | Mevcut nesne için bir karma (hash) kodu döndürür. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek türünü alır. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Mevcut nesne tarafından temsil edilen kutuya alınmış değerin türünü temsil eden değeri döndürür. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Kutu içine alınmış nesnenin sayısal değerini döndürür; eğer dönüşüm mümkün değilse sıfır döner. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneğini temsil edip etmediğini kontrol eder. C#'daki 'is' operatörünün benzeri. |
| **bool** [is](./is/)() const | Mevcut nesne tarafından temsil edilen kutuya alınmış değerin türünün **V** olup olmadığını belirler. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Mevcut nesnenin enum türünde bir kutuya alınmış değeri temsil edip etmediğini belirler. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Direkt olarak çağırın veya [LockContext](../lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) yönteminin benzeri. Özel türlerin kopyalanmasını etkinleştirir. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Belirtilen isimdeki sabit değerinin değerini belirtilen enum içinde kutuya alır. Bir parametre, enum sabitinin adını belirten dizgeyi yorumlarken büyük/küçük harf duyarlılığının göz ardı edilip edilmediğini belirtir. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Belirtilen isimdeki sabit değerinin değerini belirtilen enum içinde kutuya alır. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin dize durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](./tostring/)() const override | Mevcut nesne tarafından temsil edilen kutuya alınmış değeri dizeye dönüştürür. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Kutu içine alınmış nesneyi belirtilen biçim dizesiyle dizeye dönüştürür. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| const T\& [unbox](./unbox/)() const | Mevcut nesne tarafından temsil edilen değeri kutudan çıkarır. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Direkt olarak çağırın veya [LockContext](../lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BoxedValueBase](../boxedvaluebase/)
* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)