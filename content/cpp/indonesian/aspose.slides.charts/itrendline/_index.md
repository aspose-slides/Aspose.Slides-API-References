---
title: ITrendline
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas mewakili garis tren dari seri diagram
type: docs
weight: 1223
url: /id/aspose.slides.charts/itrendline/
---
## ITrendline kelas

Kelas mewakili garis tren dari seri diagram

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inisialisasi TextFrameForOverriding dengan teks pada parameter \"text\". Jika TextFrameForOverriding sudah diinisialisasi maka hanya mengubah teksnya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **double** [get_Backward](./get_backward/)() | Menentukan jumlah kategori (atau satuan pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang diproyeksikan. Pada diagram pencar dan non-pencar, nilai boleh berupa nilai non-negatif apa pun. Baca **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Mengembalikan diagram. Hanya-baca [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan Rsquaredvalue). Baca **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Mewakili format garis tren. Baca [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Menentukan jumlah kategori (atau satuan pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang diproyeksikan. Pada diagram pencar dan non-pencar, nilai boleh berupa nilai non-negatif apa pun. Baca **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Menentukan nilai di mana garis tren melintasi sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Baca **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lain. Nilai harus antara 2 dan 6. Baca **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Menentukan periode garis tren untuk garis rata-rata bergerak. Diabaikan untuk varian garis tren lain. Nilai harus antara 2 dan 255. Baca **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Mewakili entri legenda yang terkait dengan garis tren ini Hanya-baca [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Mengembalikan format teks diagram. Hanya-baca [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan secara otomatis. Teks yang dihasilkan secara otomatis adalah properti implisit dari label data, label satuan tampilan pada sumbu nilai, judul sumbu, judul diagram, label garis tren. Teks yang dihasilkan secara otomatis diformat dengan properti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Hanya-baca [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Mendapatkan nama garis tren. Baca [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Mendapatkan tipe garis tren. Baca [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk mengunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe referensi dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi berbagi sebesar nilai yang ditentukan. |
| virtual void [set_Backward](./set_backward/)(**double**) | Menentukan jumlah kategori (atau satuan pada diagram pencar) yang garis tren memperluas sebelum data untuk seri yang sedang diproyeksikan. Pada diagram pencar dan non-pencar, nilai boleh berupa nilai non-negatif apa pun. Tulis **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Menentukan bahwa persamaan untuk garis tren ditampilkan pada diagram (pada label yang sama dengan Rsquaredvalue). Tulis **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Menentukan bahwa nilai R-squared dari garis tren ditampilkan pada diagram (pada label yang sama dengan persamaan). Tulis **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Mewakili format garis tren. Tulis [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Menentukan jumlah kategori (atau satuan pada diagram pencar) yang garis tren memperluas setelah data untuk seri yang sedang diproyeksikan. Pada diagram pencar dan non-pencar, nilai boleh berupa nilai non-negatif apa pun. Tulis **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Menentukan nilai di mana garis tren melintasi sumbu y. Properti ini hanya didukung ketika tipe garis tren adalah exp, linear, atau poly. Tulis **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Menentukan urutan garis tren polinomial. Diabaikan untuk tipe garis tren lain. Nilai harus antara 2 dan 6. Tulis **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Menentukan periode garis tren untuk garis rata-rata bergerak. Diabaikan untuk varian garis tren lain. Nilai harus antara 2 dan 255. Tulis **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Menetapkan nama garis tren. Tulis [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Menetapkan tipe garis tren. Tulis [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-nth menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi berbagi. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan lock() C# untuk membuka kunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IOverridableText](../ioverridabletext/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)