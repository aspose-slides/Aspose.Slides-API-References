---
title: Details_NotImplementedException
second_title: Aspose.Slides için C++ API Referansı
description: "NotImplementedException, uygulanmamış ve bir taslak görevi gören bir yöntem çağrıldığında fırlatılır. Bu sınıfın örneklerini manuel olarak oluşturmayın. Bunun yerine NotImplementedException sınıfını kullanın. NotImplementedException sınıfı örneklerini System::SmartPtr içine asla sarmalamayın."
type: docs
weight: 573
url: /tr/system/details_notimplementedexception/
---
## Details_NotImplementedException sınıfı

NotImplementedException, uygulanmamış ve bir stub görevi gören bir metod çağrıldığında fırlatılır. Bu sınıfın örneklerini manuel olarak oluşturmayın. Bunun yerine NotImplementedException sınıfını kullanın. NotImplementedException sınıfı örneklerini [System::SmartPtr](../smartptr/) içine asla sarmalayın.

```cpp
class Details_NotImplementedException : public System::Details_SystemException
```

## Metodlar

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Özel istisna verileri içeren sözlüğü döndürür. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Geçerli nesne tarafından temsil edilen istisna ile ilişkili bir HRESULT kodu olan 32 bitlik tam sayı değerini döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | İç istisnayı temsil eden nesneye bir referans döndürür. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Hata açıklamasını içeren dizeyi döndürür. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Yığın izini içeren dizeyi döndürür. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | En içteki istisnayı temsil eden Exception nesnesinin bir kopyasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun bir analoğudur. Özel nesnelerin karma değerine izin verir. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının bir analoğudur. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun bir analoğudur. Özel türlerin kopyalanmasına izin verir. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'in string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'in string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Belirli bir istisna için atanmış kodlanmış sayısal değer olan HRESULT'yi ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterge (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçişine izin verir. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Geçerli nesnenin dize temsilini döndürür. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metodunu uygular; bu metod [ExceptionWrapper](../exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıfın std::exception'tan türetilmemiş olmasına rağmen türetilen sınıflar korumalı/özel üyeleri kullanarak kendi mantıklarını uygulayabilir. Bu metodun uygulanmasını [ExceptionWrapper](../exceptionwrapper/)'ye taşımak bu mantığı bozabilir. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [Details_SystemException](../details_systemexception/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)