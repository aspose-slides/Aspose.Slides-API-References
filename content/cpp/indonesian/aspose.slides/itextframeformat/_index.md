---
title: ITextFrameFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi properti pemformatan TextFrame.
type: docs
weight: 4083
url: /id/aspose.slides/itextframeformat/
---
## ITextFrameFormat kelas

Berisi properti pemformatan [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Mengembalikan teks jangkar vertikal dalam sebuah [TextFrame](../textframe/). Baca [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Mengembalikan mode autofit teks. Baca [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Jika [NullableBool::True](../nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Baca [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Mengembalikan jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tidak terdefinisi. Baca **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Mengembalikan jarak antara kolom teks di area teks (dalam poin). Ini hanya berlaku ketika ada lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Baca **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Mengembalikan atau mengatur agar teks sepenuhnya tidak berada dalam adegan 3D. Baca **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Mengembalikan margin bawah (poin) dalam sebuah [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Mengembalikan margin kiri (poin) dalam sebuah [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Mengembalikan margin kanan (poin) dalam sebuah [TextFrame](../textframe/). Baca **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Mengembalikan margin atas (poin) dalam sebuah [TextFrame](../textframe/). Baca **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya yang digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi tambahan selain rotasi teks itu sendiri. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Mengembalikan gaya teks. Hanya-baca [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan sudut khusus dalam properti RotationAngle. Baca [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Mengembalikan objek [ThreeDFormat](../threedformat/) yang mewakili properti efek 3d untuk teks. Hanya-baca [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Mendapatkan bentuk pembungkus teks. Baca [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** jika teks dibungkus pada margin [TextFrame](../textframe/). Baca [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Mendapatkan data pemformatan bingkai teks yang efektif dengan pewarisan yang diterapkan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah contoh dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Mengatur teks jangkar vertikal dalam sebuah [TextFrame](../textframe/). Tulis [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Mengatur mode autofit teks. Tulis [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Jika [NullableBool::True](../nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Mengatur jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tidak terdefinisi. Tulis **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Mengatur jarak antara kolom teks di area teks (dalam poin). Ini hanya berlaku ketika ada lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Tulis **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Mengembalikan atau mengatur agar teks sepenuhnya tidak berada dalam adegan 3D. Tulis **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Mengatur margin bawah (poin) dalam sebuah [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Mengatur margin kiri (poin) dalam sebuah [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Mengatur margin kanan (poin) dalam sebuah [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Mengatur margin atas (poin) dalam sebuah [TextFrame](../textframe/). Tulis **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya yang digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi tambahan selain rotasi teks itu sendiri. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Tulis **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan sudut khusus dalam properti RotationAngle. Tulis [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Mengatur bentuk pembungkus teks. Tulis [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** jika teks dibungkus pada margin [TextFrame](../textframe/). Tulis [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan bersama). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)