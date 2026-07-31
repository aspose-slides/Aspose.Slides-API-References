---
title: IChartTextBlockFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti pemformatan untuk elemen teks diagram.
type: docs
weight: 885
url: /id/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat kelas

Mewakili properti pemformatan untuk elemen teks diagram.

```cpp
class IChartTextBlockFormat : public virtual System::Object
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
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Mengembalikan teks jangkar vertikal dalam sebuah [TextFrame](../../aspose.slides/textframe/). Baca [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Mengembalikan mode autofit teks. Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Baca [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Jika [NullableBool::True](../../aspose.slides/nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Baca [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Mengembalikan margin bawah (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Baca **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Mengembalikan margin kiri (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Baca **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Mengembalikan margin kanan (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Baca **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Mengembalikan margin atas (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Baca **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi tambahan selain rotasi teks itu sendiri. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan sudut khusus dalam properti RotationAngle. Baca [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** jika teks dibungkus pada margin [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2007/2013). Baca [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Mengatur teks jangkar vertikal dalam sebuah [TextFrame](../../aspose.slides/textframe/). Tulis [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Mengatur mode autofit teks. Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Tulis [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Jika [NullableBool::True](../../aspose.slides/nullablebool/) maka teks harus dipusatkan secara horizontal di dalam kotak. Tulis [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Mengatur margin bawah (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Tulis **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Mengatur margin kiri (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Tulis **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Mengatur margin kanan (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Tulis **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Mengatur margin atas (point) dalam sebuah [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2013; di PowerPoint 2007 tidak berpengaruh pada render). Tulis **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi tambahan selain rotasi teks itu sendiri. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Tulis **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Menentukan orientasi teks. Nilai rotasi visual teks yang dihasilkan dirangkum dari properti ini dan sudut khusus dalam properti RotationAngle. Tulis [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** jika teks dibungkus pada margin [TextFrame](../../aspose.slides/textframe/). Mengubah properti ini dapat memberikan pengaruh tertentu hanya untuk bagian diagram berikut: [DataLabel](../datalabel/) dan [DataLabelFormat](../datalabelformat/) (dukungan penuh di PowerPoint 2007/2013). Tulis [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan penukaran pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang nama [Aspose::Slides::Charts](../)
* Pustaka [Aspose.Slides](../../)