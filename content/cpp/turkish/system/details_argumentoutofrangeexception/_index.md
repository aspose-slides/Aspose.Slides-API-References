---
title: Details_ArgumentOutOfRangeException
second_title: Aspose.Slides for C++ API Referansı
description: "ArgumentOutOfRangeException, çağrılan bir yöntem bir argüman alırken o argümanın beklenen değer aralığının dışına çıktığında fırlatılır. Bu sınıfın örneklerini manuel olarak yaratmayın. Bunun yerine ArgumentOutOfRangeException sınıfını kullanın. ArgumentOutOfRangeException sınıfı örneklerini System::SmartPtr içine sarmamaya dikkat edin."
type: docs
weight: 352
url: /tr/system/details_argumentoutofrangeexception/
---
## Details_ArgumentOutOfRangeException sınıf

ArgumentOutOfRangeException, çağrılan bir yönteme verilen argümanın beklenen değer aralığının dışına çıktığında fırlatılır. Bu sınıfın örneklerini manuel olarak oluşturmaktan kaçının. Bunun yerine ArgumentOutOfRangeException sınıfını kullanın. ArgumentOutOfRangeException sınıfı örneklerini [System::SmartPtr](../smartptr/) içine sarmaktan asla kaçın.

```cpp
class Details_ArgumentOutOfRangeException : public System::Details_ArgumentException
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Özel istisna verileri içeren bir sözlük döndürür. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Mevcut nesne tarafından temsil edilen istisna ile ilişkilendirilmiş 32-bit bir tamsayı (HRESULT kodu) döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | İç istisnayı temsil eden nesneye bir referans döndürür. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Hata açıklamasını içeren dizeyi döndürür. |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Yığın izini (stack trace) içeren dizeyi döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | En içteki istisnayı temsil eden Exception nesnesinin bir kopyasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının analoğu. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Belirli bir istisna için atanmış kodlu sayısal değer olan HRESULT'ı ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını zayıf gösterici (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Mevcut nesnenin dize temsilini döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metodunu uygular; bu yöntem [ExceptionWrapper](../exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıf std::exception'tan türetilmemiş olsa bile türetilen sınıflar korumalı/özel üyeleri kullanarak mantıklarını uygulayabilir. Bu metodun uygulamasını [ExceptionWrapper](../exceptionwrapper/)'ye taşımak bu mantığı bozabilir. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca

* Sınıf [Details_ArgumentException](../details_argumentexception/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)