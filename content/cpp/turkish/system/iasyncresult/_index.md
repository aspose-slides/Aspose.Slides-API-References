---
title: IAsyncResult
second_title: Aspose.Slides için C++ API Referansı
description: "Asenkron işlemin durumunu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı daima System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 898
url: /tr/system/iasyncresult/
---
## IAsyncResult sınıfı

Asenkron işlemin durumunu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class IAsyncResult : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [get_AsyncState](./get_asyncstate/)() | Asenkron işlem hakkında bilgi içeren bir nesne döndürür. |
| virtual [SharedPtr](../sharedptr/)\<[System::Threading::WaitHandle](../../system.threading/waithandle/)\> [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Asenkron işlemin tamamlanmasını beklemek için kullanılabilecek bir WaitHandle örneği döndürür. |
| virtual **bool** [get_CompletedSynchronously](./get_completedsynchronously/)() | Asenkron işlemin senkron olarak tamamlanıp tamamlanmadığını gösteren bir değer döndürür. |
| virtual **bool** [get_IsCompleted](./get_iscompleted/)() | Asenkron işlemin tamamlanıp tamamlanmadığını gösteren bir değer döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun analogu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'in string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'in string durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~IAsyncResult](./~iasyncresult/)() | Yıkıcı. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [smart_ptr](./smart_ptr/) | [IAsyncResult](./)'e shared işaretçi. |

## Bakınız

* Sınıf [Object](../object/)
* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)