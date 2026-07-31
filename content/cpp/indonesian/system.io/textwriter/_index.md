---
title: TextWriter
second_title: Referensi API Aspose.Slides untuk C++
description: "Kelas dasar untuk kelas yang mewakili penulis yang menulis urutan karakter ke berbagai tujuan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 443
url: /id/system.io/textwriter/
---
## TextWriter kelas

Kelas dasar untuk kelas yang mewakili penulis yang menulis urutan karakter ke berbagai tujuan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class TextWriter : public System::IDisposable
```

## Metode

| Method | Deskripsi |
| --- | --- |
| virtual void [Close](./close/)() | Menutup aliran dan melepaskan sumber daya yang diperoleh. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran yang mendasarinya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual void [Flush](./flush/)() | Mengosongkan isi buffer ke aliran yang mendasarinya. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Mengembalikan encoding yang sedang digunakan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Mengembalikan string penanda akhir baris. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Mengembalikan string penanda akhir baris. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Mengatur string penanda akhir baris. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Menulis representasi string dari objek yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan ke aliran. |
| virtual void [Write](./write/)(char_t) | Menulis karakter yang ditentukan ke aliran. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**double**) | Menulis representasi string dari nilai titik mengambang double presisi ke aliran. |
| virtual void [Write](./write/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**float**) | Menulis representasi string dari nilai titik mengambang presisi tunggal yang ditentukan ke aliran. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Menulis string yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**uint32_t**) | Menulis representasi string dari nilai integer tak bertanda 32-bit yang ditentukan ke aliran. |
| virtual void [Write](./write/)(**uint64_t**) | Menulis representasi string dari nilai integer tak bertanda 64-bit yang ditentukan ke aliran. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Menulis semua karakter dari array yang ditentukan ke aliran. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan ke aliran. |
| virtual void [Write](./write/)(const char_t *) | Menulis c-string yang ditentukan ke aliran. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan ke aliran. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat menurut format yang ditentukan ke aliran. |
| virtual void [WriteLine](./writeline/)() | Menulis karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Menulis representasi string dari objek yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(char_t) | Menulis karakter yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**double**) | Menulis representasi string dari nilai double presisi yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**float**) | Menulis representasi string dari nilai float presisi tunggal yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Menulis string yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Menulis representasi string dari nilai integer tak bertanda 32-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Menulis representasi string dari nilai integer tak bertanda 64-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Menulis semua karakter dari array yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Menulis c-string yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat menurut format yang ditentukan diikuti oleh karakter penanda akhir baris ke aliran. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke kelas ini. |

## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Ruang Nama [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)