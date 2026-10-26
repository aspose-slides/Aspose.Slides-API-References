---
title: XmlConvert
second_title: Aspose.Slides for C++ API Referansı
description: XML adlarını kodlar ve çözer, ayrıca çalışma zamanındaki tipler ile XML Şema Tanım Dili (XSD) tipleri arasında dönüşüm sağlayan yöntemler sunar. Veri tiplerini dönüştürürken döndürülen değerler yerel ayardan bağımsızdır.
type: docs
weight: 157
url: /tr/system.xml/xmlconvert/
---
## XmlConvert sınıfı

Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Bir adı çözer. Bu yöntem, XmlConvert::EncodeName(String) ve XmlConvert::EncodeLocalName(String) yöntemlerinin tersini yapar. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Adı geçerli bir XML yerel adına dönüştürür. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Adı geçerli bir XML adına dönüştürür. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Adın XML spesifikasyonuna göre geçerli olduğunu doğrular. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Verilen karakterin geçerli bir iki nokta üst üste olmayan karakter tipi olup olmadığını kontrol eder. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Argümandaki karakter geçerli bir public id karakteri ise verilen karakter örneğini döndürür, aksi takdirde **nullptr** döner. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Verilen karakterin geçerli bir Başlangıç Adı Karakteri tipi olup olmadığını kontrol eder. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Verilen karakterin geçerli bir XML boşluk karakteri olup olmadığını kontrol eder. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Verilen karakterin geçerli bir XML karakteri olup olmadığını kontrol eder. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Verilen ikili karakter çiftinin geçerli bir XML karakteri olup olmadığını kontrol eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'ıncı şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | [String](../../system/string/)'yi [Boolean](../../system/boolean/) eşdeğeri olarak dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Byte](../../system/byte/) eşdeğeri olarak dönüştürür. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Char](../../system/char/) eşdeğeri olarak dönüştürür. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [DateTime](../../system/datetime/) eşdeğeri olarak dönüştürür. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/)'yi [DateTime](../../system/datetime/) eşdeğeri olarak dönüştürür. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/)'yi [DateTime](../../system/datetime/) eşdeğeri olarak dönüştürür. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [String](../../system/string/)'yi belirtilen XmlDateTimeSerializationMode kullanarak [DateTime](../../system/datetime/)'e dönüştürür. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Sağlanan [String](../../system/string/)'yi [DateTimeOffset](../../system/datetimeoffset/) eşdeğeri olarak dönüştürür. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Sağlanan [String](../../system/string/)'yi [DateTimeOffset](../../system/datetimeoffset/) eşdeğeri olarak dönüştürür. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sağlanan [String](../../system/string/)'yi [DateTimeOffset](../../system/datetimeoffset/) eşdeğeri olarak dönüştürür. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Decimal](../../system/decimal/) eşdeğeri olarak dönüştürür. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | [String](../../system/string/)'yi [Double](../../system/double/) eşdeğeri olarak dönüştürür. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Guid](../../system/guid/) eşdeğeri olarak dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Int16](../../system/int16/) eşdeğeri olarak dönüştürür. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Int32](../../system/int32/) eşdeğeri olarak dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [Int64](../../system/int64/) eşdeğeri olarak dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [SByte](../../system/sbyte/) eşdeğeri olarak dönüştürür. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | [String](../../system/string/)'yi [Single](../../system/single/) eşdeğeri olarak dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | [Boolean](../../system/boolean/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | [Char](../../system/char/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | [SByte](../../system/sbyte/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | [Int16](../../system/int16/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | [Int32](../../system/int32/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | [Int64](../../system/int64/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | [Byte](../../system/byte/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | [UInt16](../../system/uint16/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | [UInt32](../../system/uint32/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | [UInt64](../../system/uint64/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | [Single](../../system/single/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | [Double](../../system/double/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | [TimeSpan](../../system/timespan/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | [DateTime](../../system/datetime/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [DateTime](../../system/datetime/)'yi belirtilen XmlDateTimeSerializationMode kullanarak [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Sağlanan [DateTimeOffset](../../system/datetimeoffset/)'yi [String](../../system/string/)'e dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Sağlanan [DateTimeOffset](../../system/datetimeoffset/)'yi belirtilen formatta [String](../../system/string/)'ye dönüştürür. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | [Guid](../../system/guid/)'yi [String](../../system/string/)'e dönüştürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [TimeSpan](../../system/timespan/) eşdeğeri olarak dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [UInt16](../../system/uint16/) eşdeğeri olarak dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [UInt32](../../system/uint32/) eşdeğeri olarak dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | [String](../../system/string/)'yi [UInt64](../../system/uint64/) eşdeğeri olarak dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Adın W3C Genişletilmiş İşaretleme Dili önerisine göre geçerli bir ad olup olmadığını doğrular. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Adın W3C Genişletilmiş İşaretleme Dili önerisine göre geçerli bir **NCName** olup olmadığını doğrular. **NCName**, iki nokta üst üste içermeyen bir isimdir. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Dizgenin W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes önerisine göre geçerli bir NMTOKEN olup olmadığını doğrular. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Dizgenin tüm karakterleri geçerli public id karakterleri ise verilen dizge örneğini döndürür. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Dizgenin W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes önerisine göre geçerli bir token olup olmadığını doğrular. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Dizgedeki tüm karakterler geçerli boşluk karakterleri ise verilen dizge örneğini döndürür. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Dizge argümanındaki tüm karakter ve ikili karakter çiftleri geçerli XML karakterleri ise verilen dizgeyi döndürür, aksi takdirde karşılaşılan ilk geçersiz karakter hakkında bilgi içeren bir XmlException fırlatılır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine paylaşımlı işaretçi için bir takma isimdir. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)