---
title: IAxis
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkapsulkan objek yang mewakili sumbu bagan.
type: docs
weight: 534
url: /id/aspose.slides.charts/iaxis/
---
## IAxis kelas

Mengkapsulkan objek yang mewakili sumbu bagan.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Menentukan satuan utama aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Menentukan skala satuan utama aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Menentukan nilai maksimum aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Menentukan satuan minor aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Menentukan skala satuan minor aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Menentukan nilai minimum aktual pada sumbu. Panggil metode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) sebelumnya untuk mendapatkan nilai aktual. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Mewakili tipe agregasi sumbu kategori (pembinningan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk diagram 3-D. Baca **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Menentukan lebar bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Menentukan tipe sumbu kategori. Baca [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan bagan. Hanya-baca [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Mewakili titik pada sumbu dimana sumbu tegak lurus memotongnya. Baca **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain memotongnya. Baca [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Mewakili format sumbu. Hanya-baca [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Menentukan apakah sumbu memiliki judul yang terlihat. Baca **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. Baca **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. Baca **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Menentukan nilai spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Baca **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Menentukan nilai spasi tanda tick otomatis. Jika false: gunakan properti TickMarksSpacing. Baca **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Menunjukkan apakah format terhubung ke data sumber. Baca **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. Baca **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Mewakili apakah sumbu terlihat. Baca **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Mewakili basis logaritmik. Nilai default adalah 10. Baca **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Mewakili format garis kisi utama pada sumbu bagan. Hanya-baca [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Mewakili tipe tanda tick utama untuk sumbu yang ditentukan. Baca [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Mewakili satuan utama untuk sumbu tanggal atau nilai. Baca **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Mewakili skala satuan utama untuk sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Mewakili nilai maksimum pada sumbu nilai. Baca **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Mewakili format garis kisi minor pada sumbu bagan. Hanya-baca [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Mewakili tipe tanda tick minor untuk sumbu yang ditentukan. Baca [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Mewakili skala satuan utama untuk sumbu tanggal. Baca [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Mewakili nilai minimum pada sumbu nilai. Baca **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Mewakili string format untuk Label [Axis](../axis/). Baca [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Mewakili posisi sumbu. Baca [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Mewakili apakah garis kisi utama ditampilkan. Hanya-baca **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Mewakili apakah garis kisi minor ditampilkan. Hanya-baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks bagan. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Mewakili posisi label tanda-tick pada sumbu yang ditentukan. Baca [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Mewakili sudut rotasi label tick. Baca **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Menentukan berapa banyak label tick yang dilewati di antara label yang digambar. Baca **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Mendapatkan judul sumbu. Hanya-baca [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Mewakili tipe agregasi sumbu kategori (pembinningan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk diagram 3-D. Tulis **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Menentukan lebar bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Menentukan tipe sumbu kategori. Tulis [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Mewakili titik pada sumbu dimana sumbu tegak lurus memotongnya. Tulis **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain memotongnya. Tulis [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Menentukan nilai skala unit tampilan untuk sumbu nilai. Tulis [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Menentukan apakah sumbu memiliki judul yang terlihat. Tulis **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. Tulis **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Tulis **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. Tulis **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Tulis **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Menentukan nilai spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Tulis **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Menentukan nilai spasi tanda tick otomatis. Jika false: gunakan properti TickMarksSpacing. Tulis **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Tulis **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Menunjukkan apakah format terhubung ke data sumber. Tulis **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. Tulis **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Mewakili apakah sumbu terlihat. Tulis **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Tulis **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Mewakili basis logaritmik. Nilai default adalah 10. Tulis **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Mewakili tipe tanda tick utama untuk sumbu yang ditentukan. Tulis [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Mewakili satuan utama untuk sumbu tanggal atau nilai. Tulis **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Mewakili skala satuan utama untuk sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Mewakili nilai maksimum pada sumbu nilai. Tulis **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Mewakili tipe tanda tick minor untuk sumbu yang ditentukan. Tulis [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Mewakili satuan minor untuk sumbu tanggal atau nilai. Tulis **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Mewakili skala satuan utama untuk sumbu tanggal. Tulis [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Mewakili nilai minimum pada sumbu nilai. Tulis **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Mewakili string format untuk Label [Axis](../axis/). Tulis [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Mewakili posisi sumbu. Tulis [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Mewakili posisi label tanda-tick pada sumbu yang ditentukan. Tulis [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Mewakili sudut rotasi label tick. Tulis **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Menentukan berapa banyak label tick yang dilewati di antara label yang digambar. Tulis **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Tulis **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Mengatur properti IAxis::get(set)_CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembebasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)