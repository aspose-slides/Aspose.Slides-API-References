---
title: IFormatterConverter
second_title: Aspose.Slides for C++ API Referansı
description: "System::Runtime::Serialization::SerializationInfo örneği ile veri içindeki System::Runtime::Serialization::SerializationInfo'yi ayrıştırmak için en uygun biçimlendirici tarafından sağlanan sınıf arasındaki bağlantıyı sağlar."
type: docs
weight: 27
url: /tr/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter sınıfı

[System::Runtime::Serialization::SerializationInfo](../serializationinfo/) örneği ile veri içinde [System::Runtime::Serialization::SerializationInfo](../serializationinfo/)'yi ayrıştırmak için en uygun biçimlendirici tarafından sağlanan sınıf arasındaki bağlantıyı sağlar.

```cpp
class IFormatterConverter : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | RTTI bilgisi. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) | Bir değeri verilen [System::TypeCode](../../system/typecode/)'ye dönüştürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türündeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türündeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türündeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için uzmanlaşması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için uzmanlaşması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri bool'a dönüştürür. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **uint8_t**'ye dönüştürür. |
| virtual char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri char16_t'ye dönüştürür. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri [DateTime](../../system/datetime/)'ye dönüştürür. |
| virtual [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri [Decimal](../../system/decimal/)'ye dönüştürür. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri double'a dönüştürür. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **int16_t**'ye dönüştürür. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **int32_t**'ye dönüştürür. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **int64_t**'ye dönüştürür. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **int8_t**'ye dönüştürür. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri float'a dönüştürür. |
| virtual [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri [String](../../system/string/)'ye dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesneleri string'e dönüştürmeyi sağlar. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **uint16_t**'ye dönüştürür. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **uint32_t**'ye dönüştürür. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Bir değeri **uint64_t**'ye dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğru

l çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Runtime::Serialization](../)
* Kütüphane [Aspose.Slides](../../)