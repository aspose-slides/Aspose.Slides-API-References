---
title: BinaryReader
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili sebuah pembaca yang membaca tipe data primitif sebagai data biner dalam enkoding tertentu. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 92
url: /id/system.io/binaryreader/
---
## BinaryReader kelas


Mewakili sebuah pembaca yang membaca tipe data primitif sebagai data biner dalam enkoding tertentu. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class BinaryReader : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Membuat sebuah instance dari kelas [BinaryReader](./) yang membaca data dari stream yang ditentukan menggunakan enkoding UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Membuat sebuah instance dari kelas [BinaryReader](./) yang membaca data dari stream yang ditentukan menggunakan enkoding yang ditentukan. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Membuat sebuah instance dari kelas [BinaryReader](./) yang membaca data dari stream yang ditentukan menggunakan enkoding yang ditentukan. |
| virtual void [Close](./close/)() | Menutup objek [BinaryReader](./) saat ini dan aliran masukan yang mendasarinya. |
| void [Dispose](./dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran yang mendasarinya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Mengembalikan aliran masukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| virtual int [PeekChar](./peekchar/)() | Membaca satu karakter dari aliran masukan tanpa mengubah kursor baca aliran. |
| virtual int [Read](./read/)() | Membaca satu karakter dari aliran masukan. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Membaca sejumlah byte yang ditentukan dari aliran masukan dan menuliskannya ke array byte yang ditentukan. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Membaca sejumlah karakter yang ditentukan dari aliran masukan, mengkonversinya ke enkoding UTF-16 dan menuliskan karakter UTF-16 yang dihasilkan ke array karakter yang ditentukan mulai dari posisi yang ditentukan. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Membaca satu byte dari aliran masukan dan mengembalikan representasi boolean-nya. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Membaca satu byte dari aliran masukan. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Membaca sejumlah byte yang ditentukan dari aliran masukan. |
| virtual char_t [ReadChar](./readchar/)() | Membaca satu karakter dari aliran masukan. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Membaca sejumlah karakter yang ditentukan dari aliran masukan dan mengembalikannya dalam enkoding UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | TIDAK DIIMPLEMENTASIKAN. |
| virtual **double** [ReadDouble](./readdouble/)() | Membaca 8 byte dari aliran masukan dan mengembalikannya sebagai nilai floating point double-precision. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Membaca 2 byte dari aliran masukan dan mengembalikannya sebagai nilai integer 16-bit. |
| virtual int [ReadInt32](./readint32/)() | Membaca 4 byte dari aliran masukan dan mengembalikannya sebagai nilai integer 32-bit. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Membaca 8 byte dari aliran masukan dan mengembalikannya sebagai nilai integer 64-bit. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Membaca satu byte dari aliran masukan dan mengembalikannya sebagai nilai integer 8-bit bertanda. |
| virtual **float** [ReadSingle](./readsingle/)() | Membaca 4 byte dari aliran masukan dan mengembalikannya sebagai nilai floating point single-precision. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Membaca sebuah string dari aliran saat ini. String tersebut diawali dengan panjangnya, yang dienkode sebagai integer tujuh bit sekaligus. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Membaca 2 byte dari aliran masukan dan mengembalikannya sebagai nilai integer tak bertanda 16-bit. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Membaca 4 byte dari aliran masukan dan mengembalikannya sebagai nilai integer tak bertanda 32-bit. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Membaca 8 byte dari aliran masukan dan mengembalikannya sebagai nilai integer tak bertanda 64-bit. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Pustaka [Aspose.Slides](../../)