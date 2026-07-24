---
title: TimeZone
second_title: Aspose.Slides for C++ API Referansı
description: "Bir saat dilimini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya bildirim hataları ortaya çıkar. Bu sınıf her zaman System::SmartPtr işaretçisine sarılmalı ve bu işaretçi fonksiyonlara argüman olarak geçirilmelidir."
type: docs
weight: 1327
url: /tr/system/timezone/
---
## TimeZone sınıfı

Bir saat dilimini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya bildirim hataları oluşur. Bu sınıf her zaman [System::SmartPtr](../smartptr/) işaretçisine sarılmalı ve bu işaretçi işlevlere argüman olarak geçirilmelidir.

```cpp
class TimeZone : public System::Object
```

## Metodlar

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Nesneleri C# [Object.Equals](../object/equals/) semantiğini kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | Geçerli saat dilimini temsil eden [TimeZone](./) sınıfının yeni bir örneğini döndürür. |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | Geçerli nesne tarafından temsil edilen saat diliminin yaz saati için bir ad döndürür. |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | Geçerli nesne tarafından temsil edilen saat diliminin standart zamanı için bir ad döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesne ile ilişkili referans sayacı veri yapısını alır. |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | Belirli bir yıl için yaz saati periyodunu döndürür. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) yöntemiyle benzer. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../object/gettype/) çağrısına benzer. |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | Belirtilen yerel zaman için UTC kaydırmasını döndürür. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörüne benzer. |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | Belirtilen [DateTime](../datetime/) nesnesi tarafından temsil edilen tarih ve saat değerinin, geçerli [TimeZone](./) nesnesi tarafından temsil edilen saat diliminin yaz saati aralığına düşüp düşmediğini belirler. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) muhafaza nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) yöntemine benzer. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesneyi oluşturur. Tüm iç veri yapısını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını mümkün kılar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını mümkün kılar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesidir. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) yöntemine benzer. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilitlemesini açar. Doğrudan çağırın veya [LockContext](../lockcontext/) muhafaza nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../object/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)