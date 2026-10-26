---
title: SoapHeader
second_title: Aspose.Slides için C++ API Referansı
description: "SOAP başlığının içeriğini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin bir örneğini yığın üzerinde veya operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 79
url: /tr/system.web.services.protocols/soapheader/
---
## SoapHeader sınıfı

SOAP başlığının içeriğini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığın üzerinde veya operator new kullanarak oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya assert hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class SoapHeader : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# biçiminde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# biçiminde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | SOAP sürüm 1.1 kullanıldığında SOAP başlığı alıcısının URI'sını alır. |
| **bool** [get_DidUnderstand](./get_didunderstand/)() | SOAP başlığının doğru işlenip işlenmediğini gösteren bir değeri alır. |
| [String](../../system/string/) [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | SOAP sürüm 1.1 kullanıldığında 'mustUnderstand' özniteliğinin değerini alır. |
| [String](../../system/string/) [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | SOAP sürüm 1.2 kullanıldığında 'mustUnderstand' özniteliğinin değerini alır. |
| [String](../../system/string/) [get_EncodedRelay](./get_encodedrelay/)() | ‘relay’ özniteliği değerinin dize temsilini alır. |
| **bool** [get_MustUnderstand](./get_mustunderstand/)() | SOAP başlığının anlaşılması gerekip gerekmediğini gösteren bir değeri alır. |
| **bool** [get_Relay](./get_relay/)() | ‘relay’ özniteliğinin değerini alır. |
| [String](../../system/string/) [get_Role](./get_role/)() | SOAP sürüm 1.2 kullanıldığında SOAP başlığı alıcısının URI'sını alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin bir analoğu. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneğini temsil edip etmediğini kontrol eder. C# 'is' operatörünün bir analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin bir analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özel durumu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Actor](./set_actor/)([String](../../system/string/)) | SOAP sürüm 1.1 kullanıldığında SOAP başlığı alıcısının URI'sını ayarlar. |
| void [set_DidUnderstand](./set_didunderstand/)(**bool**) | SOAP başlığının düzgün işlenip işlenmediğini gösteren bir değeri ayarlar. |
| void [set_EncodedMustUnderstand](./set_encodedmustunderstand/)([String](../../system/string/)) | SOAP sürüm 1.1 kullanıldığında 'mustUnderstand' özniteliğinin değerini ayarlar. |
| void [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)([String](../../system/string/)) | SOAP sürüm 1.2 kullanıldığında 'mustUnderstand' özniteliğinin değerini ayarlar. |
| void [set_EncodedRelay](./set_encodedrelay/)([String](../../system/string/)) | ‘relay’ özniteliği değerinin dize temsilini ayarlar. |
| void [set_MustUnderstand](./set_mustunderstand/)(**bool**) | SOAP başlığının anlaşılması gerekip gerekmediğini gösteren bir değeri ayarlar. |
| void [set_Relay](./set_relay/)(**bool**) | ‘relay’ özniteliğinin değerini ayarlar. |
| void [set_Role](./set_role/)([String](../../system/string/)) | SOAP sürüm 1.2 kullanıldığında SOAP başlığı alıcısının URI'sını ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [SoapHeader](./soapheader/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlElement](../../system.xml/xmlelement/)\>) | Yeni bir örnek oluşturur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin bir analoğu. Özelleştirilmiş nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Web::Services::Protocols](../)
* Kütüphane [Aspose.Slides](../../)