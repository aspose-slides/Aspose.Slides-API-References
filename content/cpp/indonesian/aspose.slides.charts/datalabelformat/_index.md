---
title: DataLabelFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili opsi pemformatan untuk DataLabel.
type: docs
weight: 391
url: /id/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat kelas

Mewakili opsi pemformatan untuk [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metode

| Method | Description |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Membandingkan dengan objek yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang bergaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang bergaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan grafik. Hanya-baca [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Mewakili format label data. Hanya-baca [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Baca **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Mewakili string format untuk objek DataLabels. Baca [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Mengembalikan objek Parent_Immediate. Hanya-baca [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan induk [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Hanya-baca [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Mewakili posisi label data. Baca [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada grafik. Baca [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Mewakili perilaku tampilan nilai ukuran gelembung label data pada grafik tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Mewakili perilaku tampilan nama kategori pada label data grafik tertentu. True untuk menampilkan nama kategori pada label data pada grafik. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Menentukan apakah label data pada grafik tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Mewakili perilaku tampilan nilai sel label data pada grafik tertentu. True menampilkan nilai sel. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Mewakili perilaku tampilan garis pemimpin pada label data grafik tertentu. True menampilkan garis pemimpin. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Mewakili perilaku tampilan kunci legenda label data pada grafik tertentu. True jika kunci legenda label data terlihat. Baca **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Mewakili perilaku tampilan nilai persentase label data pada grafik tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Mengembalikan Boolean untuk menunjukkan perilaku tampilan nama seri pada label data pada grafik. True untuk menampilkan nama seri. False untuk menyembunyikan. Baca **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Mewakili perilaku tampilan nilai persentase label data pada grafik tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Mengembalikan format teks grafik. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Mengembalikan kode hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Tulis **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Mewakili string format untuk objek DataLabels. Tulis [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Mewakili posisi label data. Tulis [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Mengatur atau mengembalikan Variant yang mewakili pemisah yang digunakan untuk label data pada grafik. Tulis [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Mewakili perilaku tampilan nilai ukuran gelembung label data pada grafik tertentu. True menampilkan nilai ukuran gelembung. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Mewakili perilaku tampilan nama kategori pada label data grafik tertentu. True untuk menampilkan nama kategori pada label data pada grafik. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Menentukan apakah label data pada grafik tertentu akan ditampilkan sebagai panggilan data atau sebagai label data. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Mewakili perilaku tampilan nilai sel label data pada grafik tertentu. True menampilkan nilai sel. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Mewakili perilaku tampilan garis pemimpin pada label data grafik tertentu. True menampilkan garis pemimpin. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Mewakili perilaku tampilan kunci legenda label data pada grafik tertentu. True jika kunci legenda label data terlihat. Tulis **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Mewakili perilaku tampilan nilai persentase label data pada grafik tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Mengatur Boolean untuk menunjukkan perilaku tampilan nama seri pada label data pada grafik. True untuk menampilkan nama seri. False untuk menyembunyikan. Tulis **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Mewakili perilaku tampilan nilai persentase label data pada grafik tertentu. True menampilkan nilai persentase. False untuk menyembunyikan. Tulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n sebagai pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi berbagi. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi berbagi. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [PVIObject](../../aspose.slides/pviobject/)
* Kelas [IDataLabelFormat](../idatalabelformat/)
* Ruang nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)