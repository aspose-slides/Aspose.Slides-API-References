---
title: Axis
second_title: Aspose.Slides untuk Referensi API C++
description: Membungkus objek yang mewakili sumbu bagan.
type: docs
weight: 14
url: /id/aspose.slides.charts/axis/
---
## Axis kelas

Membungkus objek yang mewakili sumbu bagan.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Menentukan unit utama aktual dari sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Menentukan skala unit utama aktual dari sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Menentukan nilai maksimum aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Menentukan unit minor aktual dari sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Menentukan skala unit minor aktual dari sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Menentukan nilai minimum aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Mewakili tipe agregasi sumbu kategori (pengelompokan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk bagan 3-D. Baca **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Menentukan satuan waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Menentukan lebar bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Menentukan tipe sumbu kategori. Baca [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan bagan induk. Baca-saja [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. Baca **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain melintasinya. Baca [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Mewakili format sumbu. Baca-saja [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Menentukan apakah sumbu memiliki judul yang terlihat. Baca **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Menunjukkan apakah unit utama sumbu ditetapkan secara otomatis. Baca **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. Baca **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Menentukan nilai spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Baca **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Menentukan nilai spasi tanda tick otomatis. Jika false: gunakan properti TickMarksSpacing. Baca **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Mewakili apakah tipe skala sumbu nilai bersifat logaritmik atau tidak. Baca **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Menunjukkan apakah format terhubung ke data sumber. Baca **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Mewakili apakah MS PowerPoint menampilkan titik data dari terakhir ke pertama. Baca **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Mewakili apakah sumbu terlihat. Baca **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Mewakili basis logaritmik. Nilai default adalah 10. Baca **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Mewakili format garis kisi utama pada sumbu bagan. Baca-saja [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Mewakili tipe tanda tick utama untuk sumbu yang ditentukan. Baca [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Mewakili unit utama untuk sumbu tanggal atau nilai. Baca **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Mewakili skala unit utama untuk sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Mewakili nilai maksimum pada sumbu nilai. Baca **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Mewakili format garis kisi minor pada sumbu bagan. Baca-saja [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Mewakili tipe tanda tick minor untuk sumbu yang ditentukan. Baca [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Mewakili unit minor untuk sumbu tanggal atau nilai. Baca **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Mewakili skala unit utama untuk sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Mewakili nilai minimum pada sumbu nilai. Baca **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Mewakili string format untuk Label [Axis](./). Baca [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Menentukan nilai khusus bin overflow. Diterapkan ketika IsAutomaticOverflowBin diatur ke false dan IsOverflowBin bernilai true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Mewakili posisi sumbu. Baca [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Untuk menyembunyikan garis kisi utama, setel [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() ke [FillType::NoFill](../../aspose.slides/filltype/). Baca-saja **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Untuk menyembunyikan garis kisi minor, setel [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() ke [FillType::NoFill](../../aspose.slides/filltype/). Baca-saja **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Mewakili format teks. Baca-saja [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Mewakili posisi label tanda tick pada sumbu yang ditentukan. Baca [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Mewakili sudut rotasi label tick. Baca **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Menentukan berapa banyak label tick yang dilewati antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Mendapatkan judul sumbu. Baca-saja [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Menentukan nilai khusus bin underflow. Diterapkan ketika IsAutomaticUnderflowBin diatur ke false dan IsUnderflowBin bernilai true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi jumlah referensi bersama sebesar nilai yang ditentukan. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Mewakili tipe agregasi sumbu kategori (pengelompokan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk bagan 3-D. Tulis **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Menentukan satuan waktu terkecil yang direpresentasikan pada sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Menentukan lebar bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Menentukan tipe sumbu kategori. Tulis [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. Tulis **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain melintasinya. Tulis [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Menentukan nilai skala unit tampilan untuk sumbu nilai. Tulis [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Menentukan apakah sumbu memiliki judul yang terlihat. Tulis **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Menunjukkan apakah unit utama sumbu ditetapkan secara otomatis. Tulis **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Tulis **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Menunjukkan apakah unit minor sumbu ditetapkan secara otomatis. Tulis **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Tulis **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Menentukan nilai spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Tulis **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Menentukan nilai spasi tanda tick otomatis. Jika false: gunakan properti TickMarksSpacing. Tulis **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Mewakili apakah tipe skala sumbu nilai bersifat logaritmik atau tidak. Tulis **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Menunjukkan apakah format terhubung ke data sumber. Tulis **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Mewakili apakah MS PowerPoint menampilkan titik data dari terakhir ke pertama. Tulis **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Mewakili apakah sumbu terlihat. Tulis **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Tulis **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Menentukan basis logaritmik. Nilai default adalah 10. Tulis **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Mewakili tipe tanda tick utama untuk sumbu yang ditentukan. Tulis [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Mewakili unit utama untuk sumbu tanggal atau nilai. Tulis **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Menentukan skala unit utama untuk sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Menentukan nilai maksimum pada sumbu nilai. Tulis **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Mewakili tipe tanda tick minor untuk sumbu yang ditentukan. Tulis [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Mewakili unit minor untuk sumbu tanggal atau nilai. Tulis **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Menentukan skala unit utama untuk sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Menentukan nilai minimum pada sumbu nilai. Tulis **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Mewakili string format untuk Label [Axis](./). Tulis [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Menentukan nilai khusus bin overflow. Diterapkan ketika IsAutomaticOverflowBin diatur ke false dan IsOverflowBin bernilai true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Mewakili posisi sumbu. Tulis [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Mewakili posisi label tanda tick pada sumbu yang ditentukan. Tulis [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Mewakili sudut rotasi label tick. Tulis **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Menentukan berapa banyak label tick yang dilewati antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Tulis **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Tulis **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Menentukan nilai khusus bin underflow. Diterapkan ketika IsAutomaticUnderflowBin diatur ke false dan IsUnderflowBin bernilai true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Mengatur properti IAxis::get(set)_CategoryAxisType dengan nilai yang ditentukan secara otomatis berdasarkan data sumbu. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Setel argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pernyataan C# lock() pembukaan kunci. Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [DomObject](../../aspose.slides/domobject/)
* Kelas [IAxis](../iaxis/)
* RuangNama [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)