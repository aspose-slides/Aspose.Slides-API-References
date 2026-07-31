---
title: TextFrameFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi properti formatTextFrameFormatting milik TextFrame.
type: docs
weight: 5461
url: /id/aspose.slides/textframeformat/
---
## TextFrameFormat kelas

Berisi properti formatTextFrameFormatting milik [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Membandingkan dengan objek yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Mengembalikan teks jangkar vertikal dalam [TextFrame](../textframe/). Baca [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Mengembalikan mode autofill teks. Baca [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Jika [NullableBool::True](../nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Baca [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Mengembalikan jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tidak terdefinisi. Baca **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Mengembalikan jarak antar kolom teks di area teks (dalam poin). Ini hanya berlaku ketika terdapat lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Baca **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Mendapatkan menjaga teks tetap datar meskipun efek Rotasi 3-D diterapkan. Baca **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Mengembalikan margin bawah (poin) dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Mengembalikan margin kiri (poin) dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Mengembalikan margin kanan (poin) dalam [TextFrame](../textframe/). Baca **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Mengembalikan margin atas (poin) dalam [TextFrame](../textframe/). Baca **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Mengembalikan objek Parent_Immediate. Baca-saja [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan [IPresentationComponent](../ipresentationcomponent/) induk. Baca-saja [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi shape terkait yang digunakan. Jika ditentukan, maka ini diterapkan secara independen dari shape. Artinya shape dapat memiliki rotasi tambahan selain rotasi yang diterapkan pada teks itu sendiri. Nilai rotasi visual teks yang dihasilkan diringkas dari properti ini dan tipe vertikal yang telah ditetapkan pada properti TextVerticalType. Baca **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan diringkas dari properti ini dan sudut khusus pada properti RotationAngle. Baca [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Mengembalikan objek [ThreeDFormat](../threedformat/) yang mewakili properti efek 3d untuk sebuah teks. Baca-saja [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Mendapatkan shape pembungkus teks. Baca [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** jika teks dibungkus pada margin [TextFrame](../textframe/). Baca [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Mendapatkan data pemformatan bingkai teks yang efektif dengan pewarisan yang diterapkan. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Mengembalikan kode hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan contoh dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengizinkan kloning tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Menetapkan teks jangkar vertikal dalam [TextFrame](../textframe/). Tulis [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Menetapkan mode autofit teks. Tulis [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Jika [NullableBool::True](../nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Tulis [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Menetapkan jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tidak terdefinisi. Tulis **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Menetapkan jarak antar kolom teks di area teks (dalam poin). Ini hanya berlaku ketika terdapat lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Tulis **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Menetapkan menjaga teks tetap datar meskipun efek Rotasi 3-D diterapkan. Tulis **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Menetapkan margin bawah (poin) dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Menetapkan margin kiri (poin) dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Menetapkan margin kanan (poin) dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Menetapkan margin atas (poin) dalam [TextFrame](../textframe/). Tulis **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi shape terkait yang digunakan. Jika ditentukan, maka ini diterapkan secara independen dari shape. Artinya shape dapat memiliki rotasi tambahan selain rotasi yang diterapkan pada teks itu sendiri. Nilai rotasi visual teks yang dihasilkan diringkas dari properti ini dan tipe vertikal yang telah ditetapkan pada properti TextVerticalType. Tulis **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan diringkas dari properti ini dan sudut khusus pada properti RotationAngle. Tulis [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Menetapkan shape pembungkus teks. Tulis [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** jika teks dibungkus pada margin [TextFrame](../textframe/). Tulis [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [TextFrameFormat](./textframeformat/)() | Menginisialisasi instance baru dari kelas [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengizinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [PVIObject](../pviobject/)
* Kelas [ITextFrameFormat](../itextframeformat/)
* Kelas [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Ruang Nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)