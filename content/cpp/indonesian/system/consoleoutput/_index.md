---
title: ConsoleOutput
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili aliran keluaran standar. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 209
url: /id/system/consoleoutput/
---
## ConsoleOutput kelas

Mewakili aliran keluaran standar. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan waktu berjalan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Menutup aliran dan melepaskan sumber daya yang diperoleh. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran yang mendasarinya. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Mengosongkan isi buffer ke aliran yang mendasarinya. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Selalu mengembalikan enkoding ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Mengembalikan objek [IFormatProvider](../iformatprovider/) yang sedang digunakan. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Mengembalikan objek [IFormatProvider](../iformatprovider/) yang sedang digunakan. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Mengembalikan string penanda akhir baris. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Mengembalikan string penanda akhir baris. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Mengatur string penanda akhir baris. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog dari metode C# [Object.ToString()](../object/tostring/). Memungkinkan konversi objek kustom ke string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Menerapkan konstruk C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(**bool**) override | Mengeluarkan representasi string dari nilai bool yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Mengeluarkan representasi string dari objek yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(char_t) override | Mengeluarkan nilai karakter yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)([Decimal](../decimal/)) override | Mengeluarkan representasi string dari nilai [Decimal](../decimal/) ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**double**) override | Mengeluarkan representasi string dari nilai floating-point double-precision ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**int32_t**) override | Mengeluarkan representasi string dari nilai integer 32-bit ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**int64_t**) override | Mengeluarkan representasi string dari nilai integer 64-bit ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**float**) override | Mengeluarkan representasi string dari nilai floating-point presisi tunggal ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const [String](../string/)\&) override | Mengeluarkan objek string yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**uint32_t**) override | Mengeluarkan representasi string dari nilai unsigned integer 32-bit ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(**uint64_t**) override | Mengeluarkan representasi string dari nilai unsigned integer 64-bit ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Mengeluarkan representasi string dari array karakter yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Mengeluarkan representasi string dari rentang nilai array karakter yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const char_t *) override | Mengeluarkan c-string yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Mengeluarkan representasi string dari objek [TypeInfo](../typeinfo/) yang ditentukan ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Menulis representasi string dari nilai integer 32-bit yang ditentukan ke aliran. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat menurut format yang ditentukan ke aliran. |
| void [WriteLine](./writeline/)() override | Mengeluarkan penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Mengeluarkan representasi string dari objek yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**bool**) override | Mengeluarkan representasi string dari nilai bool yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(char_t) override | Mengeluarkan nilai karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Mengeluarkan representasi string dari nilai [Decimal](../decimal/) diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**double**) override | Mengeluarkan representasi string dari nilai floating-point double-precision diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(int) override | Mengeluarkan representasi string dari nilai integer 32-bit diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**int64_t**) override | Mengeluarkan representasi string dari nilai integer 64-bit diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**float**) override | Mengeluarkan representasi string dari nilai floating-point presisi tunggal diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Mengeluarkan objek string yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Mengeluarkan representasi string dari nilai unsigned integer 32-bit diikuti oleh penanda akhir baris saat ini ke aliran keluaran yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Mengeluarkan representasi string dari nilai unsigned integer 64-bit diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Mengeluarkan representasi string dari array karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Mengeluarkan representasi string dari rentang nilai array karakter yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const char_t *) override | Mengeluarkan c-string yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Mengeluarkan representasi string dari objek [TypeInfo](../typeinfo/) yang ditentukan diikuti oleh penanda akhir baris saat ini ke aliran keluaan yang diwakili oleh objek saat ini. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Menulis nilai yang ditentukan diformat menurut format yang ditentukan diikuti oleh karakter terminasi baris ke aliran. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |

## Lihat Juga

* Kelas [TextWriter](../../system.io/textwriter/)
* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)