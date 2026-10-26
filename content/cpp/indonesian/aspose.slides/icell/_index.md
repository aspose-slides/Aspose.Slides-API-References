---
title: ICell
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sel dalam tabel.
type: docs
weight: 1639
url: /id/aspose.slides/icell/
---
## Kelas ICell

Mewakili sel dalam tabel.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Menentukan apakah kotak teks dipusatkan di dalam sel. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Mengembalikan objek [CellFormat](../cellformat/) yang berisi properti pemformatan untuk sel ini. Hanya-baca [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Mengembalikan jumlah kolom grid dalam tabel induk yang akan dicakup oleh sel saat ini. Properti ini memungkinkan sel tampil seolah-olah digabung, karena mereka melintasi batas vertikal sel lain dalam tabel. Hanya-baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Mendapatkan kolom pertama sel. Hanya-baca [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Mengembalikan indeks kolom pertama yang dicakup oleh sel. Hanya-baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Mendapatkan baris pertama sel. Hanya-baca [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Mengembalikan indeks baris pertama yang dicakup oleh sel. Hanya-baca **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Mengembalikan tinggi sel. Hanya-baca **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Mengembalikan true jika sel digabung dengan sel lain yang disesuaikan, false jika tidak. Hanya-baca **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Mengembalikan margin bawah dalam [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Mengembalikan margin kiri dalam [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Mengembalikan margin kanan dalam [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Mengembalikan margin atas dalam [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Mengembalikan tinggi minimum sel. Ini adalah jumlah tinggi minimal semua baris yang dicakup oleh sel. Hanya-baca **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel. Hanya-baca **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Mengembalikan jarak dari sisi atas tabel ke sisi atas sel. Hanya-baca **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal. Hanya-baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Mengembalikan objek [Table](../table/) induk untuk sel. Hanya-baca [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Mengembalikan tipe jangkar teks. Baca [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Mengembalikan kerangka teks sel. Hanya-baca [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Mengembalikan tipe teks vertikal. Baca [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Mengembalikan lebar sel. Hanya-baca **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Menentukan apakah kotak teks dipusatkan di dalam sel. Tulis **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Menetapkan margin bawah dalam [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Menetapkan margin kiri dalam [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Menetapkan margin kanan dalam [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Menetapkan margin atas dalam [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Menetapkan tipe jangkar teks. Tulis [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Menetapkan tipe teks vertikal. Tulis [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Membagi sel menjadi dua sel berdasarkan indeks kolom. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Membagi sel berdasarkan tinggi. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Membagi sel menjadi dua sel berdasarkan indeks baris. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Membagi sel berdasarkan lebar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ISlideComponent](../islidecomponent/)
* Ruang Nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)