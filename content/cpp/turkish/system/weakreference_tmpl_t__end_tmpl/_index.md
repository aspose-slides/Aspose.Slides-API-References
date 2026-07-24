---
title: WeakReference< T >
second_title: Aspose.Slides for C++ API Referansı
description: Bir nesneyi referans alırken, o nesnenin silinmesine izin veren bir zayıf referansı temsil eder.
type: docs
weight: 1509
url: /tr/system/weakreference_tmpl_t__end_tmpl/
---
## WeakReference< T > sınıf

Zayıf bir referansı temsil eder; bu referans, bir nesneyi referans alır ancak o nesnenin silinmesine izin verir.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Referans alınan nesnenin türü. |
## Metotlar

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Nesneleri C# [Object.Equals](../object/equals/) kurallarına göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Başvuru türündeki nesneleri C# biçiminde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# biçiminde karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun analoğu. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Referans alınan nesnenin null olmadığını kontrol eder. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Referans alınan nesneyi başka bir WeakReference sınıfı örneğiyle karşılaştırır. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Referans alınan nesnenin null olduğunu kontrol eder. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Referans alınan nesneyi başka bir WeakReference sınıfı örneğiyle karşılaştırır. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesi ile nullptr'i referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Mevcut WeakReference nesnesi tarafından referans alınan nesneyi (hedefi) ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon bağımsız değişkenini paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Mevcut WeakReference nesnesi tarafından referans alınan nesneyi (hedefi) alır. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [WeakReference](./weakreference/)() | Varsayılan kurucu. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | nullptr'tan kurucu. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Belirtilen nesneyi referans alan WeakReference sınıfının yeni bir örneğini başlatır. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Belirtilen nesneyi referans alan WeakReference sınıfının yeni bir örneğini başlatır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Diğer Bağlantılar

* Sınıf [Object](../object/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)