---
title: IParagraphFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas ini berisi properti pemformatan paragraf. Tidak seperti IParagraphFormatEffectiveData, semua properti kelas ini dapat ditulis.
type: docs
weight: 3147
url: /id/aspose.slides/iparagraphformat/
---
## IParagraphFormat kelas

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), semua properti kelas ini dapat ditulis.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Mengembalikan perataan teks dalam paragraf tanpa pewarisan. Baca [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Mengembalikan format bullet paragraf. Hanya-baca [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Mengembalikan format bagian default paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Mengembalikan ukuran tabulasi default tanpa pewarisan. Baca **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Mengembalikan kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Menentukan apakah pemenggalan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Mengembalikan perataan font dalam paragraf tanpa pewarisan. Baca [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Menentukan apakah tanda baca menggantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Mengembalikan Indent Baris Pertama/Indent Menggantung paragraf tanpa pewarisan. Indent Menggantung dapat didefinisikan dengan nilai negatif. Baca **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Menentukan apakah pemenggalan baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Mengembalikan margin kiri dalam paragraf tanpa pewarisan. Baca **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Mengembalikan margin kanan dalam paragraf tanpa pewarisan. Baca **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Menentukan apakah penulisan dari Kanan ke Kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Mengembalikan jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Mengembalikan jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Mengembalikan jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Mengembalikan tabulasi paragraf pada indeks yang ditentukan. Tidak ada pewarisan yang diterapkan. Hanya-baca [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Mendapatkan data pemformatan paragraf efektif dengan pewarisan yang diterapkan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Mengatur perataan teks dalam paragraf tanpa pewarisan. Tulis [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Mengatur ukuran tabulasi default tanpa pewarisan. Tulis **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Tulis **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Menentukan apakah pemenggalan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Mengatur perataan font dalam paragraf tanpa pewarisan. Tulis [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Menentukan apakah tanda baca menggantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Mengatur Indent Baris Pertama/Indent Menggantung paragraf tanpa pewarisan. Indent Menggantung dapat didefinisikan dengan nilai negatif. Tulis **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Menentukan apakah pemenggalan baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Mengatur margin kiri dalam paragraf tanpa pewarisan. Tulis **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Mengatur margin kanan dalam paragraf tanpa pewarisan. Tulis **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Menentukan apakah penulisan dari Kanan ke Kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Tulis **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Tulis **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() pembuka kunci. Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang ditetapkan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam kebanyakan kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan efektif termasuk yang diwarisi, Anda perlu menggunakan metode [IParagraphFormat::GetEffective](./geteffective/) yang mengembalikan sebuah instance [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)