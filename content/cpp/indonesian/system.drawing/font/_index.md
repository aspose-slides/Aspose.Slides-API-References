---
title: Font
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili format khusus untuk teks, termasuk jenis huruf, ukuran, dan gaya. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 79
url: /id/system.drawing/font/
---
## Font kelas

Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Font : public System::Object
```

## Metode

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Mengembalikan salinan font saat ini. |
| void [Dispose](./dispose/)() | Melepaskan semua sumber daya sistem operasi yang diperoleh oleh objek saat ini. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Menentukan apakah objek saat ini dan objek yang ditentukan identik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Membuat instance baru dari kelas [Font](./) yang mewakili font yang ada yang ditentukan dengan gaya font yang ditentukan. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Membuat instance baru dari kelas [Font](./). |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Membuat instance baru dari kelas [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Membuat instance baru dari kelas [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Membuat instance baru dari kelas [Font](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | TIDAK DIIMPLEMENTASIKAN. |
| **bool** [get_Bold](./get_bold/)() | Menentukan apakah font yang diwakili oleh objek saat ini memiliki gaya tebal yang diterapkan. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Mengembalikan keluarga font dari font yang diwakili oleh objek saat ini. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Mengembalikan gaya font dari font yang diwakili oleh objek saat ini. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Mengembalikan nilai yang menunjukkan set karakter GDI yang digunakan oleh font yang diwakili oleh objek saat ini. |
| int [get_Height](./get_height/)() | Mengembalikan jarak baris font yang diwakili oleh objek saat ini dalam piksel. |
| **bool** [get_Italic](./get_italic/)() | Menentukan apakah font yang diwakili oleh objek saat ini memiliki gaya miring yang diterapkan. |
| [String](../../system/string/) [get_Name](./get_name/)() | Mengembalikan nama wajah font yang diwakili oleh objek saat ini. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Mengembalikan nama yang awalnya ditentukan untuk font. |
| **float** [get_Size](./get_size/)() | Mengembalikan ukuran em font yang diwakili oleh objek saat ini diukur dalam satuan yang ditentukan oleh properti Unit. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Mengembalikan ukuran em font yang diwakili oleh objek saat ini dalam poin. |
| **bool** [get_Strikeout](./get_strikeout/)() | Menentukan apakah font yang diwakili oleh objek saat ini memiliki gaya coret yang diterapkan. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Mengembalikan gaya font dari font yang diwakili oleh objek saat ini. |
| **bool** [get_Underline](./get_underline/)() | Menentukan apakah font yang diwakili oleh objek saat ini memiliki gaya garis bawah yang diterapkan. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Mengembalikan satuan pengukuran untuk font yang diwakili oleh objek saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Mengembalikan jarak baris font yang diwakili oleh objek saat ini, dalam satuan saat ini dari objek [Graphics](../graphics/) yang ditentukan. |
| **float** [GetHeight](./getheight/)(**float**) | Mengembalikan tinggi font yang diwakili oleh objek saat ini ketika digambar pada perangkat tampilan dengan resolusi vertikal yang ditentukan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan pengkloningan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Pustaka [Aspose.Slides](../../)