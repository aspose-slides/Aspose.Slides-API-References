---
title: Convert
second_title: Aspose.Slides için C++ API Referansı
description: "Bir tipin değerlerini başka bir tipe dönüştüren metodları içeren yapı. Bu tip yığıt (stack) üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1561
url: /tr/system/convert/
---
## Dönüştürme yapısı

Bu yapı, bir türdeki değerleri başka bir türe dönüştüren yöntemleri içerir. Bu tür yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tür nesnelerini yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
class Convert
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | UYGULANMADI. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Unicode karakter dizisindeki bir aralık olarak temsil edilen base-64 kodlu veriyi çözer. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Base-64 kodlu veriyi bir dize olarak çözer. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Belirtilen kutulanmış değerin türünü temsil eden bir TypeCode değeri döndürür. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | UYGULANMADI. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | UYGULANMADI. Sahte bir uygulama, değerin nullptr olup olmadığını kontrol eder. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Belirtilen bayt dizisindeki bir aralık öğeyi base-64 ile kodlar ve kodlanmış veriyi Unicode karakter dizisi olarak saklar. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Belirtilen bayt dizisindeki bir aralık öğeyi base-64 ile kodlar ve kodlanmış veriyi Unicode karakter dizisi olarak saklar. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Belirtilen bayt dizisindeki öğeleri base-64 ile kodlar ve kodlanmış veriyi bir dize olarak döndürür. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Belirtilen bayt dizisindeki bir aralık öğeyi base-64 ile kodlar ve kodlanmış veriyi bir dize olarak döndürür. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Belirtilen bayt dizisindeki öğeleri base-64 ile kodlar ve kodlanmış veriyi bir dize olarak döndürür. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Belirtilen bayt dizisindeki bir aralık öğeyi base-64 ile kodlar ve kodlanmış veriyi bir dize olarak döndürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Belirtilen boolean değeri döndürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Belirtilen 8-bit işaretsiz tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Belirtilen 8-bit işaretli tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Belirtilen 16-bit işaretli tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Belirtilen 32-bit işaretli tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Belirtilen 64-bit işaretsiz tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Belirtilen 64-bit işaretli tamsayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Belirtilen float sayıyı eşdeğer bir boolean değere dönüştürür. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Belirtilen double sayıyı eşdeğer bir boolean değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer bir boolean değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Belirtilen null-dizgiyi eşdeğer bir boolean değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Belirtilen c-dizgiyi bool tipinde bir değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Belirtilen dizgeyi bool tipinde bir değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen dizgeyi bool tipinde bir değere dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer bir boolean değere dönüştürür. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Belirtilen boolean değeri eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Belirtilen 8-bit işaretsiz tamsayıyı döndürür. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Belirtilen 8-bit işaretli tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Belirtilen 16-bit işaretli tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Belirtilen 32-bit işaretli tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Belirtilen 64-bit işaretsiz tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Belirtilen 64-bit işaretli tamsayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Belirtilen float sayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Belirtilen double sayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Belirtilen unicode karakteri eşdeğer bir 8-bit işaretsiz tamsayıya dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Belirtilen null-dizgiyi eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Belirtilen sayının string temsili içeren c-dizgiyi eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Belirtilen sayının string temsili içeren dizgeyi eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Belirtilen tabanda sayının string temsili içeren dizgeyi eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının string temsili içeren dizgeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının string temsili içeren dizgeyi sağlanan biçimlendirme bilgileri ve sayı stilini kullanarak eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer bir işaretsiz 8-bit tamsayı değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(**bool**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Belirtilen 8-bit işaretsiz tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Belirtilen 8-bit işaretli tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Belirtilen 16-bit işaretsiz tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Belirtilen 16-bit işaretli tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Belirtilen 32-bit işaretsiz tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Belirtilen 32-bit işaretli tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Belirtilen 64-bit işaretsiz tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Belirtilen 64-bit işaretli tamsayıyı eşdeğer bir unicode karaktere dönüştürür. |
| static char_t [ToChar](./tochar/)(**float**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static char_t [ToChar](./tochar/)(**double**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Belirtilen unicode karakteri döndürür. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static char_t [ToChar](./tochar/)(const char_t *) | Belirtilen c-dizgenin ilk ve tek karakterini char_t değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Belirtilen dizgenin ilk ve tek karakterini char_t değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen dizgenin ilk ve tek karakterini char_t değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer bir unicode karaktere dönüştürür. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Dönüştürme desteklenmiyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Dönüştürme desteklenmıyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Dönüştürme desteklenmıyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Dönüştürme desteklenmıyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Dönüştürme desteklenmıyor. Her zaman InvalidCastException fırlatır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Belirtilen tarih ve saati döndürür. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Belirtilen dizeyi [DateTime](../datetime/) sınıfının bir örneğine dönüştürür. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak belirtilen dizeyi [DateTime](../datetime/) sınıfının bir örneğine dönüştürür. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer [DateTime](../datetime/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Belirtilen boolean değerini eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Belirtilen 32 bitlik işaretsiz tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Belirtilen 32 bitlik işaretli tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Belirtilen float sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Belirtilen double sayıyı eşdeğer ondalık sayıya dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı döndürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Bir sayının dize temsili içeren belirtilen c-dizesini eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayı stillerini ve biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer [Decimal](../decimal/) değerine dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Belirtilen boolean değerini eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Belirtilen 32 bitlik işaretsiz tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Belirtilen 32 bitlik işaretli tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Belirtilen tek duyarlıklı sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Belirtilen çift duyarlıklı sayıyı döndürür. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer çift duyarlıklı kayan nokta sayısına dönüştürür. |
| static **double** [ToDouble](./todouble/)(char_t) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Bir sayının dize temsili içeren belirtilen c-dizesini eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri çift duyarlıklı kayan nokta değerine dönüştürür. Eğer kutulanmış değerin türü [String](../string/) ise, dönüşüm sırasında belirtilen dize formatı kullanılır. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Belirtilen boolean değerini eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Belirtilen 16 bitlik işaretli tam sayıyı döndürür. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Belirtilen 32 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Belirtilen 32 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Belirtilen float sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Belirtilen double sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Belirtilen unicode karakterini eşdeğer 16 bitlik işaretli tam sayıya dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Dönüşüm desteklenmiyor. Her zaman InvalidCastException hatası fırlatılır. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Bir sayının dize temsili içeren belirtilen c-dizesini eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Belirtilen tabanda bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer 16 bitlik tam sayı değerine dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Belirtilen boolean değerini eşdeğer 32 bitlik işaretli tam sayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer 32 bitlik işaretli tam sayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Belirtilen 8 bit işaretli tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Belirtilen 16 bit işaretli tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Belirtilen 32 bit işaretli tamsayıyı döndürür. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)(**int64_t**) | Belirtilen 64 bit işaretli tamsayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)(**float**) | Belirtilen float sayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)(**double**) | Belirtilen double sayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Belirtilen unicode karakteri eşdeğer bir 32 bit işaretli tamsayıya dönüştürür. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const char_t *) | Bir sayının dize temsili içeren belirtilen C dizesini eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Bir sayının dize temsili içeren belirtilen dizeyi eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Belirtilen sayının dize temsili içeren ve belirtilen tabanda olan dizeyi eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Bir sayının dize temsili içeren belirtilen dizeyi sağlanan biçimlendirme bilgileriyle eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Bir sayının dize temsili içeren belirtilen dizeyi sağlanan biçimlendirme bilgileri ve sayı stiliyle eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer 32 bit tamsayı değerine dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Belirtilen boolean değerini eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Belirtilen 8 bit işaretsiz tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Belirtilen 8 bit işaretli tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Belirtilen 16 bit işaretli tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Belirtilen 32 bit işaretli tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Belirtilen 64 bit işaretli tamsayıyı döndürür. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Belirtilen float sayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Belirtilen double sayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Belirtilen unicode karakteri eşdeğer 64 bit işaretli tamsayıya dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Bir sayının dize temsili içeren belirtilen C dizesini eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Belirtilen sayının dize temsili içeren dizeyi eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Belirtilen sayının dize temsili içeren ve belirtilen tabanda olan dizeyi eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsili içeren belirtilen dizeyi sağlanan biçimlendirme bilgileriyle eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Bir sayının dize temsili içeren belirtilen dizeyi sağlanan biçimlendirme bilgileri ve sayı stiliyle eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer 64 bit tamsayı değerine dönüştürür. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Belirtilen boolean değerini eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Belirtilen 8 bit işaretsiz tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Belirtilen 8 bit işaretli tamsayıyı döndürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Belirtilen 16 bit işaretli tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Belirtilen 32 bit işaretli tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Belirtilen 64 bit işaretsiz tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Belirtilen 64 bit işaretli tamsayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Belirtilen float sayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Belirtilen double sayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Belirtilen unicode karakteri eşdeğer 8 bit işaretli tamsayıya dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException hatası fırlatır. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Bir sayının dize temsili içeren belirtilen C dizesini eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Belirtilen sayının dize temsili içeren dizeyi eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Belirtilen sayının dize temsili içeren ve belirtilen tabanda olan dizeyi eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsili içeren dizeyi sağlanan biçimlendirme bilgileriyle eşdeğer 8 bit işaretsiz tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Bir sayının dize temsili içeren belirtilen dizeyi sağlanan biçimlendirme bilgileri ve sayı stiliyle eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer 8 bit tamsayı değerine dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Belirtilen boolean değerini eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Belirtilen 8 bit işaretsiz tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Belirtilen 8 bit işaretli tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Belirtilen 16 bit işaretsiz tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Belirtilen 16 bit işaretli tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Belirtilen 32 bit işaretsiz tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Belirtilen 32 bit işaretli tamsayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Belirtilen 64-bit işaretsiz tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Belirtilen 64-bit işaretli tam sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Belirtilen float sayıyı döndürür. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Belirtilen çift duyarlıklı sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Belirtilen decimal sayıyı eşdeğer tek duyarlıklı kayan nokta sayısına dönüştürür. |
| static **float** [ToSingle](./tosingle/)(char_t) | Dönüştürme desteklenmez. Her zaman InvalidCastException fırlatır. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException fırlatır. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Bir sayının dize temsili içeren belirtilen c-dizesini eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Bir sayının dize temsili içeren belirtilen string'i eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgilerini kullanarak, bir sayının dize temsili içeren belirtilen string'i eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Sağlanan biçimlendirme bilgileri ve sayı biçimi kullanılarak, bir sayının dize temsili içeren belirtilen string'i eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri tek duyarlıklı kayan nokta değerine dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirtilen dize biçimi ve kültüre özgü biçim bilgilerini kullanarak, belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan belirli dize biçimi ve kültüre özgü format bilgilerini kullanarak dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Belirtilen değeri dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Belirtilen değeri, belirtilen dize biçimini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Belirtilen Unicode karakter dizisini dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen Unicode karakter dizisini, belirtilen [IFormatProvider](../iformatprovider/) nesnesi tarafından sağlanan kültüre özgü format bilgilerini kullanarak dizeye dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Belirtilen değeri döndürür; hiçbir dönüşüm yapılmaz. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Belirtilen değeri dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Belirtilen tamsayı değerini, belirtilen tabanda dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Belirtilen tamsayı değerini, belirtilen tabanda dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Belirtilen tamsayı değerini, belirtilen tabanda dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Belirtilen tamsayı değerini, belirtilen tabanda dize temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri dize temsiline dönüştürür. Kutulanmış değerin tipi [String](../string/) ise, dönüştürme sırasında belirtilen dize biçimi kullanılır. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Belirtilen Boolean değerini eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Belirtilen 16 bitlik işaretsiz tam sayıyı döndürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Belirtilen 32 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Belirtilen 32 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Belirtilen 64 bitlik işaretsiz tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Belirtilen 64 bitlik işaretli tam sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Belirtilen float sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Belirtilen double sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Belirtilen Unicode karakteri eşdeğer 16 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Dönüşüm desteklenmez. Her zaman InvalidCastException hatası fırlatır. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Belirtilen sayının dize temsilini içeren C dizesini eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Belirtilen sayının dize temsilini içeren dizeyi eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Belirtilen tabandaki sayının dize temsilini içeren dizeyi eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren dizeyi, sağlanan format bilgilerini kullanarak eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının dize temsilini içeren dizeyi, sağlanan format bilgileri ve sayı stili kullanarak eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer işaretsiz 16 bitlik tam sayı değerine dönüştürür. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Belirtilen Boolean değerini eşdeğer 32 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Belirtilen 8 bitlik işaretsiz tam sayıyı eşdeğer 32 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Belirtilen 8 bitlik işaretli tam sayıyı eşdeğer 32 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Belirtilen 16 bitlik işaretsiz tam sayıyı eşdeğer 32 bitlik işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Belirtilen 16 bitlik işaretli tam sayıyı eşdeğer 32 bitlik işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Belirtilen 32 bitlik işaretsiz tam sayıyı döndürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Belirtilen 32 bit işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Belirtilen 64 bit işaretsiz tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Belirtilen 64 bit işaretli tam sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Belirtilen float sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Belirtilen double sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Belirtilen unicode karakteri eşdeğer 32 bit işaretsiz tam sayıya dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException fırlatır. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Belirtilen sayının metin temsiline sahip c-dizesini eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Belirtilen sayının metin temsiline sahip dizeyi eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Belirtilen tabandaki sayının metin temsiline sahip dizeyi eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının metin temsiline sahip dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının metin temsiline sahip dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer işaretsiz 32 bit tamsayı değerine dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Belirtilen boolean değeri eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Belirtilen 8 bit işaretsiz tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Belirtilen 8 bit işaretli tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Belirtilen 16 bit işaretsiz tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Belirtilen 16 bit işaretli tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Belirtilen 32 bit işaretsiz tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Belirtilen 32 bit işaretli tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Belirtilen 64 bit işaretsiz tam sayıyı döndürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Belirtilen 64 bit işaretli tam sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Belirtilen float sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Belirtilen double sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Belirtilen ondalık sayıyı eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Belirtilen unicode karakteri eşdeğer 64 bit işaretsiz tam sayıya dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Dönüştürme desteklenmez. Her zaman InvalidCastException fırlatır. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Belirtilen null dizesini eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Belirtilen sayının metin temsiline sahip c-dizesini eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Belirtilen sayının metin temsiline sahip dizeyi eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Belirtilen tabandaki sayının metin temsiline sahip dizeyi eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının metin temsiline sahip dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen sayının metin temsiline sahip dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Belirtilen kutulanmış değeri eşdeğer işaretsiz 64 bit tamsayı değerine dönüştürür. |
## Ayrıca Bakınız

* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)