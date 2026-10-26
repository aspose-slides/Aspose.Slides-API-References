---
title: ISwfOptions
second_title: Aspose.Slides untuk Referensi API C++
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format SWF.
type: docs
weight: 469
url: /id/aspose.slides.export/iswfoptions/
---
## ISwfOptions kelas

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Menentukan apakah dokumen SWF yang dihasilkan harus dikompres atau tidak. Default adalah **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Mengembalikan font yang digunakan jika font sumber tidak ditemukan. Membaca [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Aktifkan/nonaktifkan menu konteks. Default adalah true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Mengembalikan gaya visual gradasi. Baca [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Menentukan kualitas gambar JPEG. \n\n Default adalah 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. \n\n Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak semestinya. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Mendapatkan alamat hyperlink lengkap untuk logo. Hanya berpengaruh jika [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) ditentukan. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Tampilkan/sembunyikan panel bawah. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Tampilkan/sembunyikan tombol layar penuh. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Tampilkan/sembunyikan panel kiri. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Tampilkan/sembunyikan pengatur langkah halaman. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Tampilkan/sembunyikan bagian pencarian. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Tampilkan/sembunyikan seluruh panel atas. Dapat diganti dalam flashvars. Default adalah true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Menentukan apakah melewati hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca **bool**. Nilai default adalah **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Mendapatkan mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). Properti ini tidak mendukung penetapan objek tipe **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Mulai dengan panel kiri terbuka. Dapat diganti dalam flashvars. Default adalah false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Mengembalikan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan berlanjut atau dibatalkan. Baca [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengizinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengizinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompres atau tidak. Default adalah **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Mengatur font yang digunakan jika font sumber tidak ditemukan. Menulis [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Aktifkan/nonaktifkan menu konteks. Default adalah true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Mengatur gaya visual gradasi. Menulis [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Menentukan kualitas gambar JPEG. \n\n Default adalah 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. \n\n Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak semestinya. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Mengatur alamat hyperlink lengkap untuk logo. Hanya berpengaruh jika [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) ditentukan. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Tampilkan/sembunyikan panel bawah. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Tampilkan/sembunyikan tombol layar penuh. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Tampilkan/sembunyikan panel kiri. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Tampilkan/sembunyikan pengatur langkah halaman. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Tampilkan/sembunyikan bagian pencarian. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Tampilkan/sembunyikan seluruh panel atas. Dapat diganti dalam flashvars. Default adalah true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Menentukan apakah melewati hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Tulis **bool**. Nilai default adalah **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). Properti ini tidak mendukung penetapan objek tipe **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Mulai dengan panel kiri terbuka. Dapat diganti dalam flashvars. Default adalah false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan berlanjut atau dibatalkan. Tulis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Mengizinkan penggantian pointer dalam container ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [ISaveOptions](../isaveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)