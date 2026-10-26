---
title: IDataLabelFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili opsi pemformatan untuk DataLabel.
type: docs
weight: 963
url: /id/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat kelas


Mewakili opsi pemformatan untuk [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan chart. Hanya baca [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Mewakili format label data. Hanya baca [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Baca **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Mewakili string format untuk objek DataLabels. Baca [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Mewakili posisi label data. Baca [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada chart. Baca [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Mewakili perilaku tampilan nilai ukuran gelembung label data pada chart tertentu. True menampilkan nilai ukuran gelembung. False menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Mewakili perilaku tampilan nama kategori label data pada chart tertentu. True untuk menampilkan nama kategori pada label data pada chart. False untuk menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Menentukan apakah label data chart tertentu akan ditampilkan sebagai data callout atau sebagai label data. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Mewakili perilaku tampilan nilai sel label data pada chart tertentu. True menampilkan nilai sel. False menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Mewakili perilaku tampilan garis pemimpin label data pada chart tertentu. True menampilkan garis pemimpin. False menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Mewakili perilaku tampilan kunci legenda label data pada chart tertentu. True jika kunci legenda label data terlihat. Baca **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Mewakili perilaku tampilan nilai persentase label data pada chart tertentu. True menampilkan nilai persentase. False menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Mengembalikan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di chart. True untuk menampilkan nama seri. False untuk menyembunyikannya. Baca **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Mewakili perilaku tampilan nilai persentase label data pada chart tertentu. True menampilkan nilai persentase. False menyembunyikannya. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks chart. Hanya baca [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Menulis **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Mewakili string format untuk objek DataLabels. Menulis [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Mewakili posisi label data. Menulis [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada chart. Menulis [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Mewakili perilaku tampilan nilai ukuran gelembung label data pada chart tertentu. True menampilkan nilai ukuran gelembung. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Mewakili perilaku tampilan nama kategori label data pada chart tertentu. True untuk menampilkan nama kategori pada label data pada chart. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Menentukan apakah label data chart tertentu akan ditampilkan sebagai data callout atau sebagai label data. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Mewakili perilaku tampilan nilai sel label data pada chart tertentu. True menampilkan nilai sel. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Mewakili perilaku tampilan garis pemimpin label data pada chart tertentu. True menampilkan garis pemimpin. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Mewakili perilaku tampilan kunci legenda label data pada chart tertentu. True jika kunci legenda label data terlihat. Menulis **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Mewakili perilaku tampilan nilai persentase label data pada chart tertentu. True menampilkan nilai persentase. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data di chart. True untuk menampilkan nama seri. False menyembunyikannya. Menulis **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Mewakili perilaku tampilan nilai persentase label data pada chart tertentu. True menampilkan nilai persentase. False menyembunyikannya. Menulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IFormattedTextContainer](../iformattedtextcontainer/)
* Ruang nama [Aspose::Slides::Charts](../)
* Pustaka [Aspose.Slides](../../)