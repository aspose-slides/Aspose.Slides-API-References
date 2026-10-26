---
title: IChartTitle
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti judul diagram.
type: docs
weight: 911
url: /id/aspose.slides.charts/icharttitle/
---
## IChartTitle kelas

Mewakili properti judul diagram.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inisialisasi TextFrameForOverriding dengan teks dalam parameter "text". Jika TextFrameForOverriding sudah diinisialisasi maka hanya mengubah teksnya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Menentukan tinggi sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Menentukan lebar sebenarnya dari elemen diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Menentukan lokasi x (kiri) sebenarnya dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Menentukan atas sebenarnya dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Mendapatkan atas elemen diagram sebagai fraksi dari tinggi diagram. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan diagram. Hanya-baca [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Mengembalikan gaya isian, garis, efek dari judul. Hanya-baca [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Menentukan tinggi elemen diagram sebagai fraksi dari tinggi diagram. Baca **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Menentukan apakah elemen diagram lain diizinkan menumpuk judul. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Mendapatkan kanan elemen diagram sebagai fraksi dari lebar diagram. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks diagram. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan secara otomatis. Teks yang dihasilkan secara otomatis adalah properti implisit dari label data, label satuan tampilan dari sumbu nilai, judul sumbu, judul diagram, label garis tren. Teks yang dihasilkan secara otomatis diformat dengan properti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Hanya-baca [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Menentukan lebar elemen diagram sebagai fraksi dari lebar diagram. Baca **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Menentukan lokasi x (kiri) elemen diagram sebagai fraksi dari lebar diagram. Baca **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Menentukan atas elemen diagram sebagai fraksi dari tinggi diagram. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instansi dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi berbagi dengan nilai yang ditentukan. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Menentukan tinggi elemen diagram sebagai fraksi dari tinggi diagram. Tulis **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Menentukan apakah elemen diagram lain diizinkan menumpuk judul. Tulis **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Menentukan lebar elemen diagram sebagai fraksi dari lebar diagram. Tulis **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Menentukan lokasi x (kiri) elemen diagram sebagai fraksi dari lebar diagram. Tulis **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Menentukan atas elemen diagram sebagai fraksi dari tinggi diagram. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi pointer lemah (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi berbagi. Tidak seharusnya dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak seharusnya dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak seharusnya dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ILayoutable](../ilayoutable/)
* Kelas [IOverridableText](../ioverridabletext/)
* Kelas [IActualLayout](../iactuallayout/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)