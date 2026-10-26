---
title: SwfOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format Swf.
type: docs
weight: 742
url: /id/aspose.slides.export/swfoptions/
---
## SwfOptions kelas


Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Metode

| Method | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_Compressed](./get_compressed/)() override | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Default adalah **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Mengembalikan font yang digunakan jika font sumber tidak ditemukan. Membaca [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Mengaktifkan/menonaktifkan menu konteks. Default adalah true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Mengembalikan gaya visual gradien. Baca [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Menentukan kualitas gambar JPEG. Default adalah 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak tepat. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Mendapatkan alamat hyperlink lengkap untuk logo. Hanya berpengaruh jika [set_LogoImageBytes()](./set_logoimagebytes/) ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Menampilkan/menyembunyikan pengatur halaman. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca **bool**. Nilai default adalah **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Mendapatkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). Properti ini tidak mendukung penetapan objek tipe [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan pengklonan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Default adalah **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Mengatur font yang digunakan jika font sumber tidak ditemukan. Menulis [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Mengaktifkan/menonaktifkan menu konteks. Default adalah true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Mengatur gaya visual gradien. Menulis [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Menentukan kualitas gambar JPEG. Default adalah 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak tepat. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Mengatur alamat hyperlink lengkap untuk logo. Hanya berpengaruh jika [set_LogoImageBytes()](./set_logoimagebytes/) ditentukan. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Menampilkan/menyembunyikan pengatur halaman. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Menulis **bool**. Nilai default adalah **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). Properti ini tidak mendukung penetapan objek tipe [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Menulis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Konstruktor default. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan


Contoh berikut menunjukkan cara mengonversi PowerPoint ke SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Lihat Juga

* Kelas [SaveOptions](../saveoptions/)
* Kelas [ISwfOptions](../iswfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Pustaka [Aspose.Slides](../../)