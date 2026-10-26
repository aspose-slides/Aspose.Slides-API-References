---
title: StringWriter
second_title: Aspose.Slides untuk Referensi API C++
description: "Mengimplementasikan TextWriter yang menulis informasi ke string. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 417
url: /id/system.io/stringwriter/
---
## StringWriter kelas

Mengimplementasikan [TextWriter](../textwriter/) yang menulis informasi ke string. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Menutup aliran dan melepaskan sumber daya yang diperoleh. |
| void [Dispose](../textwriter/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran yang mendasarinya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual void [Flush](../textwriter/flush/)() | Mengosongkan isi buffer ke aliran yang mendasarinya. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Mengembalikan enkoding yang sedang digunakan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Mengembalikan string penentu akhir baris. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Mengembalikan string penentu akhir baris. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Mengembalikan StringBuilder yang sedang digunakan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan C# lock() untuk mengunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan subclass menyalin konstruksi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan subclass menyalin konstruksi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Menetapkan string penentu akhir baris. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Membuat instance baru [StringWriter](./) menggunakan StringBuilder dan [IFormatProvider](../../system/iformatprovider/) yang ditentukan. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Membuat instance baru [StringWriter](./) menggunakan StringBuilder dan [IFormatProvider](../../system/iformatprovider/) dari budaya saat ini. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Membuat instance baru [StringWriter](./) menggunakan [IFormatProvider](../../system/iformatprovider/) yang ditentukan. |
|  [StringWriter](./stringwriter/)() | Membuat instance baru [StringWriter](./) menggunakan [IFormatProvider](../../system/iformatprovider/) dari budaya saat ini. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mengembalikan string yang mendasari. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(char_t) override | Menulis karakter yang ditentukan ke aliran. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Menulis sub-range karakter yang ditentukan dari array karakter yang diberikan ke aliran. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Menulis string yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Menulis representasi string dari objek yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**double**) | Menulis representasi string dari nilai floating-point double yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**float**) | Menulis representasi string dari nilai floating-point single-precision yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Menulis representasi string dari nilai unsigned integer 32-bit yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Menulis representasi string dari nilai unsigned integer 64-bit yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Menulis semua karakter dari array yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Menulis c-string yang ditentukan ke aliran. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan ke aliran. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat sesuai format yang diberikan ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)() | Menulis karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Menulis representasi string dari objek yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Menulis karakter yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Menulis representasi string dari nilai double-precision yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Menulis representasi string dari nilai single-precision yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Menulis string yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Menulis representasi string dari nilai unsigned integer 32-bit yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Menulis representasi string dari nilai unsigned integer 64-bit yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Menulis semua karakter dari array yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Menulis sub-range karakter UTF-16 yang ditentukan dari array karakter yang diberikan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Menulis c-string yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan diikuti oleh karakter penentu akhir baris ke aliran. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat sesuai format yang diberikan diikuti oleh karakter penentu akhir baris ke aliran. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Lihat Juga

* Kelas [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)