---
title: ChartTitle
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti judul diagram.
type: docs
weight: 326
url: /id/aspose.slides.charts/charttitle/
---
## ChartTitle kelas

Mewakili properti judul diagram.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inisialisasi TextFrameForOverriding dengan teks dalam parameter "text". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Menentukan tinggi aktual elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Menentukan lebar aktual elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Menentukan lokasi x aktual (kiri) elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Menentukan atas aktual elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bawah. Hanya-baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan diagram induk. Hanya-baca [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Mengembalikan gaya isi, garis, efek dari judul. Hanya-baca [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Mengembalikan tinggi judul sebagai fraksi dari tinggi diagram. Baca **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Menentukan apakah elemen diagram lain diizinkan menindih judul. Baca **bool**. |
| **float** [get_Right](./get_right/)() override | Kanan. Hanya-baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Mengembalikan format teks. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini akan menggantikan teks yang dihasilkan secara otomatis. Teks yang dihasilkan secara otomatis adalah properti implisit dari label data, label unit tampilan pada sumbu nilai, judul sumbu, judul diagram, label garis tren. Teks yang dihasilkan secara otomatis diformat dengan properti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Hanya-baca [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Mengembalikan lebar judul sebagai fraksi dari lebar diagram. Baca **float**. |
| **float** [get_X](./get_x/)() override | Mengembalikan koordinat x judul sebagai fraksi dari lebar diagram. Baca **float**. |
| **float** [get_Y](./get_y/)() override | Mengembalikan koordinat y judul sebagai fraksi dari tinggi diagram. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C#. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan pengkloningan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Height](./set_height/)(**float**) override | Menetapkan tinggi judul sebagai fraksi dari tinggi diagram. Tulis **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Menentukan apakah elemen diagram lain diizinkan menindih judul. Tulis **bool**. |
| void [set_Width](./set_width/)(**float**) override | Menetapkan lebar judul sebagai fraksi dari lebar diagram. Tulis **float**. |
| void [set_X](./set_x/)(**float**) override | Menetapkan koordinat x judul sebagai fraksi dari lebar diagram. Tulis **float**. |
| void [set_Y](./set_y/)(**float**) override | Menetapkan koordinat y judul sebagai fraksi dari tinggi diagram. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer di kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan lock() C#. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IChartTitle](../icharttitle/)
* Kelas [IDOMObject](../../aspose.slides/idomobject/)
* Ruang nama [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)