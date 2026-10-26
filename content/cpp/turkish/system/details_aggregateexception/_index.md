---
title: Details_AggregateException
second_title: Aspose.Slides for C++ API Referansı
description: Birden fazla iç istisna içeren bir istisnayı temsil eder.
type: docs
weight: 300
url: /tr/system/details_aggregateexception/
---
## Details_AggregateException sınıf

Birden fazla iç istisna içeren bir istisnayı temsil eder.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin bile eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin bile eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için kullanılır. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Tüm iç içe AggregateExceptions nesnelerini açarak tek düzeyli bir listeye dönüştürür. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Özel istisna verileri içeren bir sözlük döndürür. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Geçerli nesne tarafından temsil edilen istisna ile ilişkili bir HRESULT kodu olan 32 bit tamsayı değerini döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | İç istisnayı temsil eden nesneye bir referans döndürür. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Bu toplu istisna içinde bulunan iç istisna sayısını alır. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | İç istisnaların yalnızca okunabilir bir koleksiyonunu alır. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | İç istisnaların dahili dizisini döndürür. |
| [String](../string/) [get_Message](./get_message/)() const override | Tüm iç istisnalardan gelen toplu bilgiyi içerecek şekilde temel mesajı geçersiz kılar. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Yığın izini içeren dizgeyi döndürür. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | İç istisnaları yinelemeli olarak açarak kök neden istisnasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun benzeridir. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının benzeridir. |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Her iç istisna üzerinde bir işleyici fonksiyonunu çalıştırır ve işlenmemiş istisnaları yeniden fırlatır. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeridir. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitleme özelliğini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun benzeridir. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | String ve nullptr durumları için [Object::ReferenceEquals](../object/referenceequals/) özelleşmesi. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Stringler için [Object::ReferenceEquals](../object/referenceequals/) özelleşmesi. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Belirli bir istisna için atanmış kodlu sayısal değer olan HRESULT'i ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](./tostring/)() const override | Tüm iç istisnalar dahil olmak üzere istisnanın dizge temsili döndürür. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilidini açma özelliğini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metodunu uygular; bu metod [ExceptionWrapper](../exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıf std::exception'tan türetilmemiş olsa da türetilen sınıflar korumalı/özel üyeleri kullanarak mantıklarını uygulayabilir. Bu metodun uygulanmasını [ExceptionWrapper](../exceptionwrapper/)'a taşımak bu mantığı bozabilir. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Açıklamalar

Bu sınıf genellikle paralel işleme veya eşzamanlı görev yürütme senaryoları gibi aynı anda meydana gelen birden fazla istisnayı gruplamak için kullanılır. Kullanıcıların içerilen istisnaları incelemesine, düzleştirmesine veya seçici olarak ele almasına olanak tanır.

## İlgili

* Sınıf [Details_Exception](../details_exception/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)