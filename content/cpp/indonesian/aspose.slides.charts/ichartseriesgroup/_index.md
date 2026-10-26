---
title: IChartSeriesGroup
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili grup seri.
type: docs
weight: 846
url: /id/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup class


Mewakili grup seri.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan diagram. Hanya-baca [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Mengembalikan seri diagram dalam grup pada indeks yang ditentukan. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen dari ukuran area plot). Baca **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Mendapatkan sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Mengembalikan jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Baca **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Menentukan ruang antara gugusan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Menentukan format HiLowLines. HiLowLines diterapkan bersama tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Baca **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Informasi pembagian khusus untuk diagram pie-of-pie atau bar-of-pie dengan pembagian khusus. Mengembalikan titik data yang harus digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie berdasarkan indeks. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Informasi pembagian khusus untuk diagram pie-of-pie atau bar-of-pie dengan pembagian khusus. Berisi titik data yang harus digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Hanya-baca [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Menunjukkan apakah seri dalam grup ini dipetakan pada sumbu sekunder. Hanya-baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (dapat antara 5 hingga 200 persen). Baca **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Mengembalikan koleksi hanya-baca dari seri diagram. Hanya-baca [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Mengembalikan tipe dari grup seri ini. Hanya-baca [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham. Hanya-baca [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Mendapatkan elemen pada indeks yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan cloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Tulis [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Tulis **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen dari ukuran area plot). Tulis **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Tulis **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Tulis **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Menentukan ruang antara gugusan batang atau kolom, sebagai persentase lebar batang atau kolom. Tulis **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Tulis **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Tulis **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Tulis **int8_t**. |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Tulis [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Tulis **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (dapat antara 5 hingga 200 persen). Tulis **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Catatan

1) Lihat ikhtisar dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam [ChartSeriesGroup](../chartseriesgroup/) class bersifat read/write. Setiap "series group properties" dapat memiliki proyeksi hanya-baca dalam [ChartSeries](../chartseries/) class. 
## Lihat Juga

* Kelas [IChartComponent](../ichartcomponent/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Pustaka [Aspose.Slides](../../)