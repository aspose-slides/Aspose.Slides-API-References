---
title: ChartPlotArea
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili persegi panjang tempat bagan harus dipetakan.
type: docs
weight: 248
url: /id/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea kelas

Mewakili persegi panjang tempat diagram harus dipetakan.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
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
| **float** [get_ActualHeight](./get_actualheight/)() override | Menentukan tinggi sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Menentukan lebar sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Menentukan lokasi x sebenarnya (kiri) dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Menentukan atas sebenarnya dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bawah. Baca-saja **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Baca-saja [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Mengembalikan format area plot. Baca-saja [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Mengembalikan tinggi kotak pembatas area plot sebagai fraksi dari tinggi diagram (dari 0 hingga 1). Baca **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Mendefinisikan bagaimana lokasi harus dihitung: true \\u2013 dihitung secara otomatis; ditentukan oleh properti X, Y, Width, Height. Baca-saja **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau luar (termasuk sumbu dan label sumbu). Baca [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Kanan. Baca-saja **float**. |
| **float** [get_Width](./get_width/)() override | Mengembalikan lebar kotak pembatas area plot sebagai fraksi dari lebar diagram (dari 0 hingga 1). Baca **float**. |
| **float** [get_X](./get_x/)() override | Mengembalikan koordinat x sudut kiri atas kotak pembatas area plot sebagai fraksi dari lebar diagram (dari 0 hingga 1). Baca **float**. |
| **float** [get_Y](./get_y/)() override | Mengembalikan koordinat y sudut kiri atas kotak pembatas area plot sebagai fraksi dari tinggi diagram (dari 0 hingga 1). Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Periksa apakah objek mewakili contoh tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Height](./set_height/)(**float**) override | Menetapkan tinggi kotak pembatas area plot sebagai fraksi dari tinggi diagram (dari 0 hingga 1). Tulis **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari bagian dalamnya (tidak termasuk sumbu dan label sumbu) atau luar (termasuk sumbu dan label sumbu). Tulis [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Menetapkan lebar kotak pembatas area plot sebagai fraksi dari lebar diagram (dari 0 hingga 1). Tulis **float**. |
| void [set_X](./set_x/)(**float**) override | Menetapkan koordinat x sudut kiri atas kotak pembatas area plot sebagai fraksi dari lebar diagram (dari 0 hingga 1). Tulis **float**. |
| void [set_Y](./set_y/)(**float**) override | Menetapkan koordinat y sudut kiri atas kotak pembatas area plot sebagai fraksi dari tinggi diagram (dari 0 hingga 1). Tulis **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [DomObject](../../aspose.slides/domobject/)
* Kelas [IChartPlotArea](../ichartplotarea/)
* Ruang nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)