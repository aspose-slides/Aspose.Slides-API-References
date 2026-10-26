---
title: ChartSeriesGroup
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili grup seri.
type: docs
weight: 300
url: /id/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup kelas

Mewakili grup seri.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
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
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan diagram induk. Baca-saja [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Mengembalikan seri diagram dalam grup pada indeks yang ditentukan. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Menentukan ukuran lubang pada diagram donat (dapat antara 0 dan 90 persen dari ukuran area plot). Baca **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Mendapatkan sudut irisan pie atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Baca **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Mengembalikan jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Baca **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Menentukan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom. Baca **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | True jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Baca **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Menentukan seberapa banyak batang dan kolom harus saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% sampai 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Menentukan cara menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Informasi pembagian khusus untuk diagram pie-of-pie atau bar-of-pie dengan pembagian khusus. Mengembalikan titik data yang harus digambar pada pie atau batang kedua dalam diagram pie-of-pie atau bar-of-pie berdasarkan indeks. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Informasi pembagian khusus untuk diagram pie-of-pie atau bar-of-pie dengan pembagian khusus. Berisi titik data yang harus digambar pada pie atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Baca-saja [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. Baca-saja **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Menentukan ukuran pie atau batang kedua dari diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pie pertama (dapat antara 5 dan 200 persen). Baca **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Mengembalikan koleksi seri. Baca-saja [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Mengembalikan tipe grup seri ini. Baca-saja [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Menyediakan akses ke batang naik/turun pada diagram Garis atau Stok. Baca-saja [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Mendapatkan elemen pada indeks yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Tulis [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Tulis **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Menentukan ukuran lubang pada diagram donat (dapat antara 0 dan 90 persen dari ukuran area plot). Tulis **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Mengatur sudut irisan pie atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Tulis **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Tulis **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Menentukan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom. Tulis **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | True jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Tulis **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Tulis **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% sampai 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Menentukan cara menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Tulis [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Tulis **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Menentukan ukuran pie atau batang kedua dari diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pie pertama (dapat antara 5 dan 200 persen). Tulis **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properties grup seri"). "Properties grup seri" dalam kelas [ChartSeriesGroup](./) bersifat baca/tulis. Setiap "properties grup seri" dapat memiliki proyeksi baca-saja dalam kelas [ChartSeries](../chartseries/). 

## Lihat Juga

* Kelas [IChartSeriesGroup](../ichartseriesgroup/)
* Kelas [IDOMObject](../../aspose.slides/idomobject/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)