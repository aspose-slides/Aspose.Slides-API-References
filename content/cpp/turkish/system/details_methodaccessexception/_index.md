---
title: Details_MethodAccessException
second_title: Aspose.Slides for C++ API Referansı
description: "MemberAccessException, mevcut olmayan bir yönteme erişim denenmesi veya yönteme erişimin izin verilmemesi durumunda fırlatılır. Bu sınıfın örneklerini manuel olarak oluşturmayın. Bunun yerine MethodAccessException sınıfını kullanın. MethodAccessException sınıfı örneklerini System::SmartPtr içine asla sarmalamayın."
type: docs
weight: 560
url: /tr/system/details_methodaccessexception/
---
## Details_MethodAccessException sınıf

MemberAccessException, mevcut olmayan bir yönteme erişim denenmesi veya yönteme erişimin izin verilmemesi durumunda fırlatılır. Bu sınıfın örneklerini manuel olarak oluşturmayın. Bunun yerine MethodAccessException sınıfını kullanın. MethodAccessException sınıfı örneklerini [System::SmartPtr](../smartptr/) içine asla sarmalamayın.

```cpp
class Details_MethodAccessException : public System::Details_MemberAccessException
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN’in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN’in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Özel istisna verileri içeren sözlüğü döndürür. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Geçerli nesne tarafından temsil edilen istisna ile ilişkili bir HRESULT kodu olan 32-bit tamsayı değerini döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | İç istisnayı temsil eden nesneye bir referans döndürür. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Hata açıklamasını içeren dizeyi döndürür. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Yığın izini (stack trace) içeren dizeyi döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | En içteki istisnayı temsil eden Exception nesnesinin bir kopyasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun bir benzeridir. Özel nesnelerin hash'lenmesini sağlar. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının bir benzeridir. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitleme kısmını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun bir benzeridir. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin dize ve nullptr durumları için uzmanlaşması. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin dize durumları için uzmanlaşması. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Belirli bir istisna için atanmış kodlanmış sayısal değer olan HRESULT'ı ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Geçerli nesnenin dize temsilini döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açma kısmını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metodunu uygular; bu metod [ExceptionWrapper](../exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıfın std::exception'dan türetilmemiş olmasına rağmen türetilen sınıflar, mantıklarını uygulamak için korumalı/özel üyeleri kullanabilir. Bu metodun uygulamasını [ExceptionWrapper](../exceptionwrapper/)'ye taşımak o mantığı bozabilir. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Details_MemberAccessException](../details_memberaccessexception/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)