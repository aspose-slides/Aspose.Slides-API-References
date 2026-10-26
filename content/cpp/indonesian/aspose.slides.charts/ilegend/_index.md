---
title: ILegend
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti legenda diagram.
type: docs
weight: 1080
url: /id/aspose.slides.charts/ilegend/
---
## ILegend kelas

Mewakili properti legenda diagram.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang ala C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang ala C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Menentukan tinggi sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Menentukan lebar sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Menentukan lokasi x (kiri) sebenarnya dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Menentukan bagian atas sebenarnya dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Mendapatkan bagian atas elemen diagram sebagai pecahan dari tinggi diagram. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan diagram. Hanya-baca [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Mendapatkan entri legenda. Hanya-baca [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Mendapatkan properti entri legenda yang sesuai dengan titik data dalam diagram pada indeks yang ditentukan. Untuk jenis diagram: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, titik data diambil dari seri pertama. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Mengembalikan format legenda. Hanya-baca [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Menentukan tinggi elemen diagram sebagai pecahan dari tinggi diagram. Baca **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Menentukan apakah elemen diagram lain diizinkan menimpa legenda. Baca **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Menentukan posisi legenda pada diagram. Nilai non-NaN dari properti X, Y, Width, Heigt menimpa efek properti ini. Baca [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Mendapatkan kanan elemen diagram sebagai pecahan dari lebar diagram. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks diagram. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Menentukan lebar elemen diagram sebagai pecahan dari lebar diagram. Baca **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Menentukan lokasi x (kiri) elemen diagram sebagai pecahan dari lebar diagram. Baca **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Menentukan bagian atas elemen diagram sebagai pecahan dari tinggi diagram. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan contoh tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, benar-benar, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, benar-benar, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Menentukan tinggi elemen diagram sebagai pecahan dari tinggi diagram. Tulis **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Menentukan apakah elemen diagram lain diizinkan menimpa legenda. Tulis **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Menentukan posisi legenda pada diagram. Nilai non-NaN dari properti X, Y, Width, Height menimpa efek properti ini. Tulis [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Menentukan lebar elemen diagram sebagai pecahan dari lebar diagram. Tulis **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Menentukan lokasi x (kiri) elemen diagram sebagai pecahan dari lebar diagram. Tulis **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Menentukan bagian atas elemen diagram sebagai pecahan dari tinggi diagram. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ILayoutable](../ilayoutable/)
* Kelas [IFormattedTextContainer](../iformattedtextcontainer/)
* Kelas [IActualLayout](../iactuallayout/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)