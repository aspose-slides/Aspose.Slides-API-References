---
title: Legend
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti legenda grafik.
type: docs
weight: 1262
url: /id/aspose.slides.charts/legend/
---
## Legend kelas

Mewakili properti legenda grafik.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
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
| **float** [get_ActualHeight](./get_actualheight/)() override | Menentukan tinggi sebenarnya dari elemen grafik. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Menentukan lebar sebenarnya dari elemen grafik. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Menentukan lokasi x (kiri) sebenarnya dari elemen grafik relatif terhadap sudut kiri atas grafik. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Menentukan posisi atas elemen grafik relatif terhadap sudut kiri atas grafik. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bagian bawah. **float** hanya-baca. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan grafik. [IChart](../ichart/) hanya-baca. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Mendapatkan entri legenda. [ILegendEntryCollection](../ilegendentrycollection/) hanya-baca. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Mendapatkan properti entri legenda yang sesuai dengan titik data pada grafik pada indeks yang ditentukan. Untuk tipe grafik: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, titik data diambil dari seri pertama. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Mengembalikan format legenda. [IFormat](../iformat/) hanya-baca. |
| **float** [get_Height](./get_height/)() override | Mengembalikan tinggi legenda sebagai fraksi dari tinggi grafik. Baca **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Menentukan apakah elemen grafik lain diizinkan menimpa legenda. Baca **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Menentukan posisi legenda pada grafik. Nilai bukan-NaN dari properti X, Y, Width, Heigt menggantikan efek properti ini. Baca [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Kanan. **float** hanya-baca. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Format teks. [IChartTextFormat](../icharttextformat/) hanya-baca. |
| **float** [get_Width](./get_width/)() override | Mengembalikan lebar legenda sebagai fraksi dari lebar grafik. Baca **float**. |
| **float** [get_X](./get_x/)() override | Mengembalikan koordinat x legenda sebagai fraksi dari lebar grafik. Baca **float**. |
| **float** [get_Y](./get_y/)() override | Mengembalikan koordinat y legenda sebagai fraksi dari tinggi grafik. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Height](./set_height/)(**float**) override | Menetapkan tinggi legenda sebagai fraksi dari tinggi grafik. Tulis **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Menentukan apakah elemen grafik lain diizinkan menimpa legenda. Tulis **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Menentukan posisi legenda pada grafik. Nilai bukan-NaN dari properti X, Y, Width, Height menggantikan efek properti ini. Tulis [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Menetapkan lebar legenda sebagai fraksi dari lebar grafik. Tulis **float**. |
| void [set_X](./set_x/)(**float**) override | Menetapkan koordinat x legenda sebagai fraksi dari lebar grafik. Tulis **float**. |
| void [set_Y](./set_y/)(**float**) override | Menetapkan koordinat y legenda sebagai fraksi dari tinggi grafik. Tulis **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Menetapkan argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [DomObject](../../aspose.slides/domobject/)
* Kelas [ILegend](../ilegend/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)