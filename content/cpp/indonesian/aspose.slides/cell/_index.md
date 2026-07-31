---
title: Cell
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sebuah sel dalam tabel.
type: docs
weight: 300
url: /id/aspose.slides/cell/
---
## Kelas Cell

Mewakili sebuah sel dalam tabel.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik [Object.Equals](../../system/object/equals/) C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Menentukan apakah kotak teks berada di tengah dalam sel atau tidak. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Mengembalikan objek [CellFormat](../cellformat/) yang berisi properti pemformatan untuk sel ini. Hanya-baca [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Mengembalikan jumlah kolom kisi dalam grid tabel induk yang akan dicakup oleh sel saat ini. Properti ini memungkinkan sel memiliki tampilan digabung, karena mereka melintasi batas vertikal sel lain dalam tabel. Hanya-baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Mendapatkan kolom pertama dari sel. Hanya-baca [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Mengembalikan indeks kolom pertama yang dicakup oleh sel. Hanya-baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Mendapatkan baris pertama dari sel. Hanya-baca [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Mengembalikan indeks baris pertama yang dicakup oleh sel. Hanya-baca **int32_t**. |
| **double** [get_Height](./get_height/)() override | Mengembalikan tinggi sel. Hanya-baca **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Mengembalikan true jika sel digabung dengan sel lain yang disesuaikan, false jika tidak. Hanya-baca **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Mengembalikan margin bawah dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Mengembalikan margin kiri dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Mengembalikan margin kanan dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Mengembalikan margin atas dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Mengembalikan tinggi minimum sebuah sel. Ini adalah jumlah dari tinggi minimum semua baris yang ditutupi oleh sel. Hanya-baca **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel. Hanya-baca **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Mengembalikan jarak dari sisi atas tabel ke sisi atas sel. Hanya-baca **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Mengembalikan presentasi induk dari sebuah sel. Hanya-baca [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal. Hanya-baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Mengembalikan slide induk dari sebuah sel. Hanya-baca [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Mengembalikan objek [Table](../table/) induk untuk sebuah sel. Hanya-baca [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Mengembalikan tipe jangkar teks. Baca [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Mengembalikan bingkai teks dari sebuah sel. Hanya-baca [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Mengembalikan tipe teks vertikal. Baca [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Mengembalikan lebar sel. Hanya-baca **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Menentukan apakah kotak teks berada di tengah dalam sel atau tidak. Tulis **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Menetapkan margin bawah dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Menetapkan margin kiri dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Menetapkan margin kanan dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Menetapkan margin atas dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Menetapkan tipe jangkar teks. Tulis [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Menetapkan tipe teks vertikal. Tulis [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Membagi sel menjadi dua sel berdasarkan indeks kolom. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Membagi sel berdasarkan tinggi. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Membagi sel menjadi dua sel berdasarkan indeks baris. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Membagi sel berdasarkan lebar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IDOMObject](../idomobject/)
* Kelas [ICell](../icell/)
* Ruang nama [Aspose::Slides](../)
* Library [Aspose.Slides](../../)