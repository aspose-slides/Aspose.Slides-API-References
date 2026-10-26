---
title: Convert
second_title: Aspose.Slides untuk Referensi API C++
description: "Struktur yang berisi metode-metode untuk melakukan konversi nilai dari satu tipe ke nilai tipe lainnya. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 1561
url: /id/system/convert/
---
## Struktur Konversi

Struktur yang berisi metode yang melakukan konversi nilai dari satu tipe ke nilai tipe lain. Tipe ini harus dialokasikan di stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
class Convert
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | BELUM DIIMPLEMENTASIKAN. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Mendekode data yang dienkode base-64 yang direpresentasikan sebagai rentang dalam array karakter Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Mendekode data yang dienkode base-64 yang direpresentasikan sebagai string. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Mengembalikan nilai TypeCode yang mewakili tipe dari nilai boxed yang ditentukan. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | BELUM DIIMPLEMENTASIKAN. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | BELUM DIIMPLEMENTASIKAN Implementasi palsu, memeriksa apakah nilai adalah nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Mengenkripsi base-64 rentang elemen dalam array byte yang ditentukan dan menyimpan data terenkripsi sebagai array karakter Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Mengenkripsi base-64 rentang elemen dalam array byte yang ditentukan dan menyimpan data terenkripsi sebagai array karakter Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Mengenkripsi base-64 elemen dalam array byte yang ditentukan dan mengembalikan data terenkripsi sebagai string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Mengenkripsi base-64 rentang elemen dalam array byte yang ditentukan dan mengembalikan data terenkripsi sebagai string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Mengenkripsi base-64 elemen dalam array byte yang ditentukan dan mengembalikan data terenkripsi sebagai string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Mengenkripsi base-64 rentang elemen dalam array byte yang ditentukan dan mengembalikan data terenkripsi sebagai string. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Mengembalikan nilai boolean yang ditentukan. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Mengonversi 8-bit unsigned integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Mengonversi 8-bit signed integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Mengonversi 16-bit unsigned integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Mengonversi 16-bit signed integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Mengonversi 32-bit unsigned integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Mengonversi 32-bit signed integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Mengonversi 64-bit unsigned integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Mengonversi 64-bit signed integer yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Mengonversi angka float yang ditentukan ke nilai boolean yang setara. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Mengonversi angka double yang ditentukan ke nilai boolean yang setara. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan ke nilai boolean yang setara. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai boolean yang setara. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Mengonversi c-string yang ditentukan ke nilai tipe bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Mengonversi string yang ditentukan ke nilai tipe bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan ke nilai tipe bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan ke nilai boolean yang setara. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Mengonversi nilai boolean yang ditentukan ke 8-bit unsigned integer yang setara. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Mengembalikan 8-bit unsigned integer yang ditentukan. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Mengonversi 8-bit signed integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Mengonversi 16-bit unsigned integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Mengonversi 16-bit signed integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Mengonversi 32-bit unsigned integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Mengonversi 32-bit signed integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Mengonversi 64-bit unsigned integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Mengonversi 64-bit signed integer yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Mengonversi angka float yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Mengonversi angka double yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Mengonversi karakter unicode yang ditentukan ke 8-bit unsigned integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai unsigned 8-bit integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai unsigned 8-bit integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai unsigned 8-bit integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai unsigned 8-bit integer yang setara. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai unsigned 8-bit integer yang setara menggunakan informasi format yang diberikan. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai unsigned 8-bit integer yang setara menggunakan informasi format dan gaya angka yang diberikan. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan ke nilai unsigned 8-bit integer yang setara. |
| static char_t [ToChar](./tochar/)(**bool**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Mengonversi 8-bit unsigned integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Mengonversi 8-bit signed integer yang ditentukan ke karakter unicode yang setara. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Mengonversi 16-bit unsigned integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Mengonversi 16-bit signed integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Mengonversi 32-bit unsigned integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Mengonversi 32-bit signed integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Mengonversi 64-bit unsigned integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Mengonversi 64-bit signed integer yang ditentukan ke karakter unicode yang setara. |
| static char_t [ToChar](./tochar/)(**float**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Mengembalikan karakter unicode yang ditentukan. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Mengonversi karakter pertama dan satu-satunya dari c-string yang ditentukan ke nilai char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Mengonversi karakter pertama dan satu-satunya dari string yang ditentukan ke nilai char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi karakter pertama dan satu-satunya dari string yang ditentukan ke nilai char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan ke karakter unicode yang setara. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Mengembalikan tanggal dan waktu yang ditentukan. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Mengonversi string yang ditentukan menjadi sebuah instance dari kelas [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan menjadi sebuah instance dari kelas [DateTime](../datetime/) menggunakan informasi format yang disediakan. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan menjadi nilai [DateTime](../datetime/) yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Mengonversi nilai boolean yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Mengonversi bilangan bulat bertanda 8-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Mengonversi bilangan bulat bertanda 16-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Mengonversi bilangan bulat bertanda 32-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Mengonversi bilangan bulat bertanda 64-bit yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Mengonversi angka float yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Mengonversi angka double yang ditentukan menjadi angka desimal yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Mengembalikan angka desimal yang ditentukan. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Mengonversi string null yang ditentukan menjadi nilai [Decimal](../decimal/) yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai [Decimal](../decimal/) yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai [Decimal](../decimal/) yang setara. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai [Decimal](../decimal/) menggunakan informasi format yang disediakan. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai [Decimal](../decimal/) menggunakan gaya angka yang ditentukan dan informasi format. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan menjadi nilai [Decimal](../decimal/) yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Mengonversi nilai boolean yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Mengonversi bilangan bulat bertanda 8-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Mengonversi bilangan bulat bertanda 16-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Mengonversi bilangan bulat bertanda 32-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Mengonversi bilangan bulat bertanda 64-bit yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Mengonversi angka single presisi yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Mengembalikan angka double yang ditentukan. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan menjadi angka floating-point double presisi yang setara. |
| static **double** [ToDouble](./todouble/)(char_t) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Mengonversi string null yang ditentukan menjadi nilai floating-point double presisi yang setara. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara menggunakan informasi format yang disediakan. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara menggunakan informasi format yang disediakan dan gaya angka. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan menjadi nilai floating-point double presisi. Jika tipe nilai boxed adalah [String](../string/), format string yang ditentukan digunakan selama konversi. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Mengonversi nilai boolean yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Mengonversi bilangan bulat bertanda 8-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Mengembalikan bilangan bulat bertanda 16-bit yang ditentukan. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Mengonversi bilangan bulat bertanda 32-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Mengonversi bilangan bulat bertanda 64-bit yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Mengonversi angka float yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Mengonversi angka double yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Mengonversi karakter unicode yang ditentukan menjadi bilangan bulat bertanda 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Mengonversi string null yang ditentukan menjadi nilai bilangan bulat 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai bilangan bulat 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai bilangan bulat 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan menjadi nilai bilangan bulat 16-bit yang setara. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai bilangan bulat 16-bit yang setara menggunakan informasi format yang disediakan. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai bilangan bulat 16-bit yang setara menggunakan informasi format yang disediakan dan gaya angka. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan menjadi nilai bilangan bulat 16-bit yang setara. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Mengonversi nilai boolean yang ditentukan menjadi bilangan bulat bertanda 32-bit yang setara. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan menjadi bilangan bulat bertanda 32-bit yang setara. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Mengonversi integer bertanda 8-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Mengonversi integer tak bertanda 16-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Mengonversi integer bertanda 16-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Mengonversi integer tak bertanda 32-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Mengembalikan integer bertanda 32-bit yang ditentukan. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Mengonversi integer tak bertanda 64-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(**int64_t**) | Mengonversi integer bertanda 64-bit yang ditentukan ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(**float**) | Mengonversi angka float ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(**double**) | Mengonversi angka double ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal ke integer bertanda 32-bit yang ekuivalen. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Mengonversi karakter unicode ke integer bertanda 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai integer 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 32-bit yang ekuivalen. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang ekuivalen menggunakan informasi pemformatan yang diberikan. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang ekuivalen menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai kotak ke nilai integer 32-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Mengonversi nilai boolean ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Mengonversi integer tak bertanda 8-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Mengonversi integer bertanda 8-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Mengonversi integer tak bertanda 16-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Mengonversi integer bertanda 16-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Mengonversi integer tak bertanda 32-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Mengonversi integer bertanda 32-bit ke integer bertanda 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Mengonversi integer tak bertanda 64-bit ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Mengembalikan integer bertanda 64-bit yang ditentukan. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Mengonversi angka float ke integer bertanda 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Mengonversi angka double ke integer bertanda 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal ke integer bertanda 64-bit yang ekuivalen. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Mengonversi karakter unicode ke integer bertanda 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai integer 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 64-bit yang ekuivalen. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang ekuivalen menggunakan informasi pemformatan yang diberikan. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang ekuivalen menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai kotak ke nilai integer 64-bit yang ekuivalen. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Mengonversi nilai boolean ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Mengonversi integer tak bertanda 8-bit ke integer bertanda 8-bit yang ekuivalen. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Mengembalikan integer bertanda 8-bit yang ditentukan. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Mengonversi integer tak bertanda 16-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Mengonversi integer bertanda 16-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Mengonversi integer tak bertanda 32-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Mengonversi integer bertanda 32-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Mengonversi integer tak bertanda 64-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Mengonversi integer bertanda 64-bit ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Mengonversi angka float ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Mengonversi angka double ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Mengonversi karakter unicode ke integer bertanda 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai integer 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 8-bit yang ekuivalen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit tak bertanda yang ekuivalen menggunakan informasi pemformatan yang diberikan. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit yang ekuivalen menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai kotak ke nilai integer 8-bit yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Mengonversi nilai boolean ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Mengonversi integer tak bertanda 8-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Mengonversi integer bertanda 8-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Mengonversi integer tak bertanda 16-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Mengonversi integer bertanda 16-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Mengonversi integer tak bertanda 32-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Mengonversi integer bertanda 32-bit ke angka floating-point presisi tunggal yang ekuivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Mengonversi integer tak bertanda 64-bit yang ditentukan menjadi angka floating-point presisi tunggal yang ekivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Mengonversi integer bertanda 64-bit yang ditentukan menjadi angka floating-point presisi tunggal yang ekivalen. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Mengembalikan angka float yang ditentukan. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Mengonversi angka double presisi menjadi angka floating-point presisi tunggal yang ekivalen. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan menjadi angka floating-point presisi tunggal yang ekivalen. |
| static **float** [ToSingle](./tosingle/)(char_t) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Mengonversi null-string yang ditentukan menjadi nilai floating-point presisi tunggal yang ekivalen. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang ekivalen. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang ekivalen. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang ekivalen menggunakan informasi pemformatan yang disediakan. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang ekivalen menggunakan informasi pemformatan yang disediakan dan gaya angka. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai boxed yang ditentukan menjadi nilai floating-point presisi tunggal. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Mengonversi nilai yang ditentukan menjadi representasi stringnya. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi string menggunakan informasi format khusus budaya. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya menggunakan format string yang ditentukan dan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Mengonversi nilai yang ditentukan ke string. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Mengonversi nilai yang ditentukan ke string menggunakan format string yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Mengonversi array karakter unicode yang ditentukan ke string. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi array karakter unicode yang ditentukan ke string menggunakan informasi format budaya-spesifik yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Mengembalikan nilai yang ditentukan; tidak ada konversi yang dilakukan. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Mengonversi nilai yang ditentukan ke representasi string-nya. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Mengonversi nilai integer yang ditentukan ke representasi string-nya dalam basis yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Mengonversi nilai integer yang ditentukan ke representasi string-nya dalam basis yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Mengonversi nilai integer yang ditentukan ke representasi string-nya dalam basis yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Mengonversi nilai integer yang ditentukan ke representasi string-nya dalam basis yang ditentukan. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai kotak yang ditentukan ke representasi string-nya. Jika tipe nilai kotak adalah [String](../string/), format string yang ditentukan digunakan selama konversi. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Mengonversi nilai boolean yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Mengonversi bilangan bulat bertanda 8-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Mengembalikan bilangan bulat tak bertanda 16-bit yang ditentukan. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Mengonversi bilangan bulat bertanda 16-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Mengonversi bilangan bulat bertanda 32-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Mengonversi bilangan bulat bertanda 64-bit yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Mengonversi bilangan bertipe float yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Mengonversi bilangan bertipe double yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Mengonversi bilangan desimal yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Mengonversi karakter unicode yang ditentukan ke bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Mengonversi null-string yang ditentukan ke nilai bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Mengonversi c-string yang berisi representasi string sebuah angka ke nilai bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string sebuah angka dalam basis yang ditentukan ke nilai bilangan bulat tak bertanda 16-bit yang setara. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai bilangan bulat tak bertanda 16-bit yang setara menggunakan informasi format yang disediakan. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai bilangan bulat tak bertanda 16-bit yang setara menggunakan informasi format dan gaya angka yang disediakan. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai kotak yang ditentukan ke nilai bilangan bulat tak bertanda 16-bit yang setara. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Mengonversi nilai boolean yang ditentukan ke bilangan bulat tak bertanda 32-bit yang setara. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan ke bilangan bulat tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Mengonversi bilangan bulat bertanda 8-bit yang ditentukan ke bilangan bulat tak bertanda 32-bit yang setara. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan ke bilangan bulat tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Mengonversi bilangan bulat bertanda 16-bit yang ditentukan ke bilangan bulat tak bertanda 32-bit yang setara. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Mengembalikan bilangan bulat tak bertanda 32-bit yang ditentukan. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Mengonversi integer bertanda 32-bit yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Mengonversi integer tak bertanda 64-bit yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Mengonversi integer bertanda 64-bit yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Mengonversi angka float yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Mengonversi angka double yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Mengonversi karakter unicode yang ditentukan ke integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Mengonversi string null yang ditentukan ke nilai integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Mengonversi c-string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string sebuah angka dalam basis yang ditentukan ke nilai integer tak bertanda 32-bit yang setara. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 32-bit yang setara menggunakan informasi format yang disediakan. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 32-bit yang setara menggunakan informasi format dan gaya angka yang disediakan. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang dibungkus ke nilai integer tak bertanda 32-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Mengonversi nilai boolean yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Mengonversi integer tak bertanda 8-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Mengonversi integer bertanda 8-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Mengonversi integer tak bertanda 16-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Mengonversi integer bertanda 16-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Mengonversi integer tak bertanda 32-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Mengonversi integer bertanda 32-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Mengembalikan integer tak bertanda 64-bit yang ditentukan. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Mengonversi integer bertanda 64-bit yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Mengonversi angka float yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Mengonversi angka double yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Mengonversi angka desimal yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Mengonversi karakter unicode yang ditentukan ke integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Konversi tidak didukung. Selalu melempar InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Mengonversi string null yang ditentukan ke nilai integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Mengonversi c-string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Mengonversi string yang berisi representasi string sebuah angka dalam basis yang ditentukan ke nilai integer tak bertanda 64-bit yang setara. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 64-bit yang setara menggunakan informasi format yang disediakan. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang berisi representasi string sebuah angka ke nilai integer tak bertanda 64-bit yang setara menggunakan informasi format dan gaya angka yang disediakan. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi nilai yang dibungkus ke nilai integer tak bertanda 64-bit yang setara. |
## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)