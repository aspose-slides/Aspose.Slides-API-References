---
title: Trendline
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas mewakili garis tren dari seri diagram
type: docs
weight: 1366
url: /id/aspose.slides.charts/trendline/
---
## Trendline kelas

Kelas mewakili garis tren dari seri diagram

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metode

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inisialisasi TextFrameForOverriding dengan teks dalam parameter \"text\". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| **double** [get_Backward](./get_backward/)() override | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Baca **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Mengembalikan diagram induk. Hanya-baca [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Menentukan bahwa persamaan garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). Baca **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Mewakili format garis tren. Baca [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Baca **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Menentukan nilai dimana garis tren memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lainnya. Nilai harus antara 2 dan 6. Baca **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Menentukan periode garis tren untuk garis rata-rata bergerak. Diabaikan untuk variasi garis tren lainnya. Nilai harus antara 2 dan 255. Baca **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Mewakili entri legenda yang terkait dengan garis tren ini. Hanya-baca [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Mengembalikan format teks. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan otomatis dari label data. Teks yang dihasilkan otomatis berarti teks yang dikelola oleh properti ShowSeriesName, ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat. Hanya-baca [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Mendapatkan nama garis tren. Baca [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Mendapatkan tipe garis tren. Baca [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan C# lock() untuk mengunci. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Inisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruksi subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruksi subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Backward](./set_backward/)(**double**) override | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas sebelum data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Tulis **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Menentukan bahwa persamaan garis tren ditampilkan pada diagram (dalam label yang sama dengan Rsquaredvalue). Tulis **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (dalam label yang sama dengan persamaan). Tulis **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Mewakili format garis tren. Tulis [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Menentukan jumlah kategori (atau unit pada diagram sebar) yang garis tren memperluas setelah data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa nilai non-negatif apa pun. Tulis **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Menentukan nilai dimana garis tren memotong sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Tulis **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lainnya. Nilai harus antara 2 dan 6. Tulis **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Menentukan periode garis tren untuk rata-rata bergerak. Diabaikan untuk variasi garis tren lainnya. Nilai harus antara 2 dan 255. Tulis **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Menetapkan nama garis tren. Tulis [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Menetapkan tipe garis tren. Tulis [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Menetapkan argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [DomObject](../../aspose.slides/domobject/)
* Kelas [ITrendline](../itrendline/)
* Ruang nama [Aspose::Slides::Charts](../)
* Pustaka [Aspose.Slides](../../)