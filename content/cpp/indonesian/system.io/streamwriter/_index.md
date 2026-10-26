---
title: StreamWriter
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili penulis yang menulis karakter ke aliran byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject() . Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan error runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 391
url: /id/system.io/streamwriter/
---
## StreamWriter kelas

Mewakili penulis yang menulis karakter ke aliran byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan error runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metode

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Menutup stream dan melepaskan sumber daya yang diperoleh. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup stream yang mendasarinya. |
| virtual void [Dispose](./dispose/)(**bool**) | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup stream yang mendasarinya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flush](./flush/)() override | Membuang isi buffer ke stream yang mendasarinya dan kemudian membuang stream yang mendasarinya. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Mengembalikan nilai yang menunjukkan apakah [StreamWriter](./) akan membuang data ke stream yang mendasarinya setiap kali metode [StreamWriter::Write](./write/) dipanggil. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Mengembalikan pointer bersama ke objek yang merepresentasikan stream yang mendasarinya. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Mengembalikan encoding yang sedang digunakan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Mengembalikan objek [IFormatProvider](../../system/iformatprovider/) yang sedang digunakan. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Mengembalikan string penanda akhir baris. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Mengembalikan string penanda akhir baris. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Mengembalikan nilai yang menentukan apakah [StreamWriter](./) harus membuang data ke stream yang mendasarinya setiap kali metode [StreamWriter::Write](./write/) dipanggil. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Menetapkan string penanda akhir baris. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (daripada shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke stream yang mendasarinya menggunakan encoding UTF-8 dan buffer dengan ukuran default 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke stream yang mendasarinya menggunakan encoding yang ditentukan dan buffer dengan ukuran default 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke stream yang mendasarinya menggunakan encoding yang ditentukan dan buffer berukuran yang ditentukan. Parameter menentukan apakah stream yang mendasarinya harus ditutup saat objek [StreamWriter](./) dibuang. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke file yang ditentukan menggunakan encoding UTF-8 dan buffer dengan ukuran default 1024 byte. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke file yang ditentukan menggunakan encoding yang ditentukan dan buffer dengan ukuran default 1024 byte. Parameter menentukan apakah data harus ditambahkan ke file atau file harus ditimpa. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Membuat instance objek [StreamWriter](./) yang menulis karakter ke file yang ditentukan menggunakan encoding yang ditentukan dan ukuran buffer. Parameter menentukan apakah data harus ditambahkan ke file atau file harus ditimpa. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(char_t) override | Menulis karakter yang ditentukan ke stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Menulis string yang ditentukan ke stream. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Menulis representasi string dari objek yang ditentukan ke stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Menulis semua karakter dari array yang ditentukan ke stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan ke stream. |
| void [Write](./write/)(const char_t *) override | Menulis c-string yang ditentukan ke stream. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Menulis representasi string dari objek yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Menulis representasi string dari nilai floating point double-precision yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Menulis representasi string dari nilai floating point single-precision yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Menulis representasi string dari nilai unsigned 32-bit yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Menulis representasi string dari nilai unsigned 64-bit yang ditentukan ke stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan ke stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai-nilai yang ditentukan dengan format yang ditentukan ke stream. |
| void [WriteLine](./writeline/)() override | Menulis karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Menulis string yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Menulis representasi string dari objek yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Menulis semua karakter dari array yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const char_t *) override | Menulis c-string yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Menulis representasi string dari objek yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Menulis representasi string dari nilai boolean yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Menulis karakter yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Menulis representasi string dari objek [Decimal](../../system/decimal/) yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Menulis representasi string dari nilai floating point double-precision yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Menulis representasi string dari nilai integer 64-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Menulis representasi string dari nilai floating point single-precision yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Menulis representasi string dari nilai unsigned 32-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Menulis representasi string dari nilai unsigned 64-bit yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Menulis representasi string dari objek [TypeInfo](../../system/typeinfo/) yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Menulis nilai-nilai yang ditentukan dengan format yang ditentukan diikuti oleh karakter penanda akhir baris ke stream. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
|  [~StreamWriter](./~streamwriter/)() | Destruktor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Lihat Juga

* Kelas [TextWriter](../textwriter/)
* Ruang Nama [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)