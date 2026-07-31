---
title: ParagraphFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas ini berisi properti pemformatan paragraf. Tidak seperti IParagraphFormatEffectiveData, semua properti kelas ini dapat ditulis.
type: docs
weight: 4668
url: /id/aspose.slides/paragraphformat/
---
## ParagraphFormat kelas


Kelas ini berisi properti pemformatan paragraf. Tidak seperti [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), semua properti kelas ini dapat ditulis.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Membandingkan dengan objek yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Mengembalikan perataan teks dalam paragraf tanpa pewarisan. Baca [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Mengembalikan ukuran tabulasi default tanpa pewarisan. Baca **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Menentukan apakah jeda baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Mengembalikan perataan font dalam paragraf tanpa pewarisan. Baca [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Mengembalikan Indent Baris Pertama/Hanging Indent paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Baca **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Menentukan apakah jeda baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Mengembalikan margin kiri dalam paragraf tanpa pewarisan. Baca **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Mengembalikan margin kanan dalam paragraf tanpa pewarisan. Baca **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Mengembalikan objek Parent_Immediate. Hanya-baca [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan induk [IPresentationComponent](../ipresentationcomponent/). Hanya-baca [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Menentukan apakah penulisan Right to Left (kanan ke kiri) digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Mengembalikan jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Mengembalikan jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Mengembalikan jumlah ruang antara baris dasar dalam paragraf. Nilai positif berarti persentase, nilai negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Mengembalikan tabulasi paragraf pada indeks yang ditentukan. Tidak ada pewarisan yang diterapkan. Hanya-baca [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Mendapatkan data pemformatan paragraf efektif dengan pewarisan diterapkan. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Mengembalikan kode hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor kelas turunan. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor kelas turunan. |
|  [ParagraphFormat](./paragraphformat/)() | Menginisialisasi instance baru dari [ParagraphFormat](./) kelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama dengan nilai yang ditentukan. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Mengatur perataan teks dalam paragraf tanpa pewarisan. Tulis [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Mengatur ukuran tabulasi default tanpa pewarisan. Tulis **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Menentukan apakah jeda baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Mengatur perataan font dalam paragraf tanpa pewarisan. Tulis [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Mengatur Indent Baris Pertama/Hanging Indent paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Tulis **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Menentukan apakah jeda baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Mengatur margin kiri dalam paragraf tanpa pewarisan. Tulis **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Mengatur margin kanan dalam paragraf tanpa pewarisan. Tulis **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Menentukan apakah penulisan Right to Left (kanan ke kiri) digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Tulis **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Tulis **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Mengatur jumlah ruang antara baris dasar dalam paragraf. Nilai positif berarti persentase, nilai negatif berarti ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan penguncian pernyataan C# lock() untuk melepaskan kunci. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Catatan


Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan ketika mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan efektif termasuk yang diwarisi, Anda perlu menggunakan metode [ParagraphFormat::GetEffective](./geteffective/) yang mengembalikan instance [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).
## Lihat Juga

* Kelas [PVIObject](../pviobject/)
* Kelas [IParagraphFormat](../iparagraphformat/)
* Kelas [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Ruang Nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)