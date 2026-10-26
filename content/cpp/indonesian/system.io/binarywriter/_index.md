---
title: BinaryWriter
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili penulis yang menulis nilai tipe primitif ke aliran byte. Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena hal itu akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 105
url: /id/system.io/binarywriter/
---
## BinaryWriter kelas


Mewakili penulis yang menulis nilai tipe primitif ke aliran byte. Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena hal itu akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Membuat sebuah instance dari kelas [BinaryWriter](./) yang menulis data ke aliran yang ditentukan menggunakan pengkodean yang ditentukan. |
| void [Close](./close/)() | Menutup objek [BinaryWriter](./) saat ini serta aliran keluaran yang mendasarinya. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran yang mendasarinya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flush](./flush/)() | Membersihkan aliran keluaran. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Mengembalikan aliran keluaran. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan pengkloningan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan untuk subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salinan untuk subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi berbagi sebesar nilai yang ditentukan. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Mengatur posisi aliran yang diwakili oleh objek saat ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer menjadi mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi berbagi. Tidak boleh dipanggil secara langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak boleh dipanggil secara langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; sebaiknya gunakan smart pointer atau ThisProtector. |
| virtual void [Write](./write/)(**uint8_t**) | Menulis nilai integer tak bertanda 8-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**bool**) | Menulis satu byte dengan nilai 0 jika **value** 'true' dan 1 jika **value** 'false' ke aliran keluaran. |
| virtual void [Write](./write/)(char16_t) | Menulis nilai karakter lebar 16-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**int16_t**) | Menulis nilai integer 16-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(int) | Menulis nilai integer 32-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**int64_t**) | Menulis nilai integer 64-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**uint16_t**) | Menulis nilai integer tak bertanda 16-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**uint32_t**) | Menulis nilai integer tak bertanda 32-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**uint64_t**) | Menulis nilai integer tak bertanda 64-bit yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**float**) | Menulis nilai titik mengambang presisi tunggal yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(**double**) | Menulis nilai titik mengambang presisi ganda yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Menulis representasi byte dari nilai [Decimal](../../system/decimal/) yang ditentukan ke aliran keluaran. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Menulis string berprefiks panjang dalam pengkodean saat ini ke aliran keluaran. |
| virtual void [Write](./write/)(const char_t *) | Menulis string berprefiks panjang dalam pengkodean saat ini ke aliran keluaran. |
|  [~BinaryWriter](./~binarywriter/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Ruang nama [System::IO](../)
* Pustaka [Aspose.Slides](../../)