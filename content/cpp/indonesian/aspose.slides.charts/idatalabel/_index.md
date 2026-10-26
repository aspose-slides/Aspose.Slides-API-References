---
title: IDataLabel
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili label seri.
type: docs
weight: 937
url: /id/aspose.slides.charts/idatalabel/
---
## IDataLabel kelas

Mewakili label seri.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Metode

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inisialisasi TextFrameForOverriding dengan teks pada parameter \"text\". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Menentukan tinggi aktual elemen chart. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Menentukan lebar aktual elemen chart. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Menentukan lokasi x (kiri) elemen chart relatif terhadap sudut kiri atas chart. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Menentukan bagian atas elemen chart relatif terhadap sudut kiri atas chart. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) terlebih dahulu untuk mendapatkan nilai aktual. Baca **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Mendapatkan bagian atas elemen chart sebagai pecahan dari tinggi chart. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan chart. Hanya-baca [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Mengembalikan format label data. Hanya-baca [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Menentukan tinggi elemen chart sebagai pecahan dari tinggi chart. Baca **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False berarti label data tidak terlihat (dan semua flag Show* (ShowValue, ...) menjadi false). Hanya-baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Mendapatkan sisi kanan elemen chart sebagai pecahan dari lebar chart. Hanya-baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks chart. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan secara otomatis. Teks yang dihasilkan secara otomatis adalah properti implisit dari label data, label unit tampilan pada sumbu nilai, judul sumbu, judul chart, label garis tren. Teks yang dihasilkan secara otomatis diformat dengan properti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Hanya-baca [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Mendapatkan sel data workbook. Diterapkan jika properti IDataLabelFormat::get(set)_ShowLabelValueFromCell bernilai true. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Menentukan lebar elemen chart sebagai pecahan dari lebar chart. Baca **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Menentukan lokasi x (kiri) elemen chart sebagai pecahan dari lebar chart. Baca **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Menentukan bagian atas elemen chart sebagai pecahan dari tinggi chart. Baca **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Mengembalikan teks label aktual berdasarkan pengaturan [DataLabelFormat](../datalabelformat/) atau nilai TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Menyembunyikan label data dengan mengatur semua flag Show* (ShowValue, ...) ke keadaan false. IsVisible akan menjadi false setelah ini. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk mengunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruksi salinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruksi salinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Menentukan tinggi elemen chart sebagai pecahan dari tinggi chart. Tulis **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Menetapkan sel data workbook. Diterapkan jika properti IDataLabelFormat::get(set)_ShowLabelValueFromCell bernilai true. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Menentukan lebar elemen chart sebagai pecahan dari lebar chart. Tulis **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Menentukan lokasi x (kiri) elemen chart sebagai pecahan dari lebar chart. Tulis **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Menentukan bagian atas elemen chart sebagai pecahan dari tinggi chart. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan unlock() C# untuk membuka kunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ILayoutable](../ilayoutable/)
* Kelas [IOverridableText](../ioverridabletext/)
* Kelas [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)