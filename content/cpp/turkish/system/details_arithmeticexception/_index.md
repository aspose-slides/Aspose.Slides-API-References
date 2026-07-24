---
title: Details_ArithmeticException
second_title: Aspose.Slides C++ için API Referansı
description: "ArithmeticException, aritmetik işlemlerin yürütülmesi veya dönüşüm/kast işlemleri sırasında bir hata oluştuğunda fırlatılır. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine ArithmeticException sınıfını kullanın. ArithmeticException sınıfı örneklerini System::SmartPtr içine asla sarmalamayın."
type: docs
weight: 365
url: /tr/system/details_arithmeticexception/
---
## Details_ArithmeticException sınıf

ArithmeticException, aritmetik işlemlerin yürütülmesi veya dönüştürme/kast işlemleri sırasında bir hata oluştuğunda fırlatılır. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine ArithmeticException sınıfını kullanın. ArithmeticException sınıfı örneklerini [System::SmartPtr](../smartptr/) içine asla sarmalamayın.

```cpp
class Details_ArithmeticException : public System::Details_SystemException
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objeleri C# [Object.Equals](../object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Özel istisna verileriyle bir sözlük döndürür. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Geçerli nesnenin temsil ettiği istisna ile ilişkili olan HRESULT kodunu içeren 32-bit tamsayı değerini döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | İç istisna nesnesini temsil eden bir referans döndürür. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Hata açıklamasını içeren dizeyi döndürür. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Yığın izini (stack trace) içeren dizeyi döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | En içteki istisna nesnesini temsil eden Exception nesnesinin bir kopyasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun benzeridir. Özel nesnelerin hashlenmesini sağlar. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının benzeridir. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun benzeridir. Özel tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) öğesinin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) öğesinin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Belirli bir istisnaya atanmış kodlanmış sayısal değer olan HRESULT'i ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf göstergeç (weak pointer) olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki göstergeleri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Geçerli nesnenin dize temsilini döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metodunu uygular; bu metod [ExceptionWrapper](../exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıf std::exception'tan türetilmemiş olsa da türetilen sınıflar korumalı/özel üyeleri kullanarak mantıklarını uygulayabilir. Bu metodun uygulanmasını [ExceptionWrapper](../exceptionwrapper/)'a taşımak bu mantığı bozabilir. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Details_SystemException](../details_systemexception/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)