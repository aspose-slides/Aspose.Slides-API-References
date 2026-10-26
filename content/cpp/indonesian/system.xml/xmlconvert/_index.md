---
title: XmlConvert
second_title: Referensi API Aspose.Slides untuk C++
description: Menyandi dan mendekode nama XML, serta menyediakan metode untuk mengonversi antara tipe runtime dan tipe bahasa definisi skema XML (XSD). Saat mengonversi tipe data, nilai yang dikembalikan bersifat independen terhadap locale.
type: docs
weight: 157
url: /id/system.xml/xmlconvert/
---
## XmlConvert kelas

Menyandi dan mendekode nama XML, serta menyediakan metode untuk mengonversi antara tipe runtime dan tipe bahasa definisi XML [Schema](../../system.xml.schema/) (XSD). Saat mengonversi tipe data, nilai yang dikembalikan bersifat independen terhadap locale.

```cpp
class XmlConvert : public System::Object
```

## Metode

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Mendekode sebuah nama. Metode ini melakukan kebalikan dari metode XmlConvert::EncodeName(String) dan XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Mengonversi nama menjadi nama lokal XML yang valid. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Mengonversi nama menjadi nama XML yang valid. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Memverifikasi bahwa nama valid menurut spesifikasi XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Memeriksa apakah karakter yang diberikan merupakan tipe karakter non-kolon yang valid. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Mengembalikan instance karakter yang diberikan jika karakter dalam argumen merupakan karakter id publik yang valid, jika tidak **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Memeriksa apakah karakter yang diberikan merupakan tipe Start Name Character yang valid. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Memeriksa apakah karakter yang diberikan merupakan karakter spasi putih XML yang valid. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Memeriksa apakah karakter yang diberikan merupakan karakter XML yang valid. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Memeriksa apakah pasangan surrogate karakter yang diberikan merupakan karakter XML yang valid. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Mengonversi [String](../../system/string/) menjadi ekivalen [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Mengonversi [String](../../system/string/) menjadi [DateTime](../../system/datetime/) menggunakan XmlDateTimeSerializationMode yang ditentukan. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Mengonversi [String](../../system/string/) yang diberikan menjadi ekivalen [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Mengonversi [String](../../system/string/) menjadi ekivalen [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Mengonversi [String](../../system/string/) menjadi ekivalen [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Mengonversi [Boolean](../../system/boolean/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Mengonversi [Char](../../system/char/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Mengonversi [Decimal](../../system/decimal/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Mengonversi [SByte](../../system/sbyte/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Mengonversi [Int16](../../system/int16/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Mengonversi [Int32](../../system/int32/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Mengonversi [Int64](../../system/int64/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Mengonversi [Byte](../../system/byte/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Mengonversi [UInt16](../../system/uint16/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Mengonversi [UInt32](../../system/uint32/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Mengonversi [UInt64](../../system/uint64/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Mengonversi [Single](../../system/single/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Mengonversi [Double](../../system/double/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Mengonversi [TimeSpan](../../system/timespan/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Mengonversi [DateTime](../../system/datetime/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Mengonversi [DateTime](../../system/datetime/) menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Mengonversi [DateTime](../../system/datetime/) menjadi [String](../../system/string/) menggunakan XmlDateTimeSerializationMode yang ditentukan. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Mengonversi [DateTimeOffset](../../system/datetimeoffset/) yang diberikan menjadi [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Mengonversi [DateTimeOffset](../../system/datetimeoffset/) yang diberikan menjadi [String](../../system/string/) dalam format yang ditentukan. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Mengonversi [Guid](../../system/guid/) menjadi [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Mengonversi [String](../../system/string/) menjadi ekivalen [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Memverifikasi bahwa nama merupakan nama yang valid menurut rekomendasi W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Memverifikasi bahwa nama merupakan **NCName** yang valid menurut rekomendasi W3C Extended Markup Language. **NCName** adalah nama yang tidak dapat mengandung titik dua. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Memverifikasi bahwa string merupakan NMTOKEN yang valid menurut rekomendasi W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Mengembalikan instance string yang diberikan jika semua karakter dalam argumen string merupakan karakter id publik yang valid. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Memverifikasi bahwa string merupakan token yang valid menurut rekomendasi W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Mengembalikan instance string yang diberikan jika semua karakter dalam argumen string merupakan karakter spasi putih yang valid. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Mengembalikan string yang diberikan jika semua karakter dan pasangan surrogate dalam argumen string merupakan karakter XML yang valid, jika tidak akan dilemparkan XmlException dengan informasi tentang karakter tidak valid pertama yang ditemui. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance dari kelas ini. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)