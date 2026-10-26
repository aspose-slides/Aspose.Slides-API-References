---
title: PdfOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Pdf.
type: docs
weight: 573
url: /id/aspose.slides.export/pdfoptions/
---
## PdfOptions kelas

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Metode

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Mengembalikan array nama keluarga font yang ditentukan pengguna yang [Aspose.Slides](../../aspose.slides/) harus menganggap sebagai umum. Baca [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Menerapkan warna transparan yang ditentukan ke gambar jika **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke **bool**.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Mengembalikan font yang digunakan jika font sumber tidak ditemukan. Baca [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True untuk menggambar bingkai hitam di sekitar setiap slide. Baca **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Menentukan apakah semua karakter font harus disertakan atau hanya subset yang digunakan. Baca **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Menentukan apakah [Aspose.Slides](../../aspose.slides/) akan menyertakan font umum untuk teks ASCII (rentang kode 33..127). [Fonts](../../aspose.slides/fonts/) untuk kode karakter lebih dari 127 selalu disertakan. Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna. Baca **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Mengembalikan gaya visual gradien. Baca [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Mendapatkan warna transparan gambar. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True untuk mengonversi semua data OLE dari presentasi menjadi berkas tertanam dalam PDF yang dihasilkan. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Menyediakan opsi yang mengontrol tampilan objek [Ink](../../aspose.slides.ink/) dalam dokumen yang diekspor. Hanya-baca [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Mengembalikan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Mengatur kata sandi pengguna untuk melindungi dokumen PDF. Baca [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Menunjukkan apakah teks harus diubah menjadi bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Menentukan apakah akan melewati hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca **bool**. Nilai default adalah **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Mendapatkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Mengembalikan nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Menentukan tipe kompresi yang akan digunakan untuk semua konten tekstual dalam dokumen. Baca [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentri [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
|  [PdfOptions](./pdfoptions/)() | Konstruktor default. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Menetapkan array nama keluarga font yang ditentukan pengguna yang [Aspose.Slides](../../aspose.slides/) harus menganggap sebagai umum. Tulis [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Menerapkan warna transparan yang ditentukan ke gambar jika **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke **bool**.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Tulis [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Menetapkan font yang digunakan jika font sumber tidak ditemukan. Menulis [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True untuk menggambar bingkai hitam di sekitar setiap slide. Tulis **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Menentukan apakah semua karakter font harus disertakan atau hanya subset yang digunakan. Tulis **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Menentukan apakah [Aspose.Slides](../../aspose.slides/) akan menyertakan font umum untuk teks ASCII (33..127). [Fonts](../../aspose.slides/fonts/) untuk kode karakter lebih dari 127 selalu disertakan. Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna. Tulis **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Menetapkan gaya visual gradien. Tulis [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Menetapkan warna transparan gambar. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True untuk mengonversi semua data OLE dari presentasi menjadi berkas tertanam dalam PDF yang dihasilkan. Tulis **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Menetapkan nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Tulis **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Mengatur kata sandi pengguna untuk melindungi dokumen PDF. Tulis [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Menunjukkan apakah teks harus diubah menjadi bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Tulis **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Tulis **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Menentukan apakah akan melewati hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Tulis **bool**. Nilai default adalah **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Menetapkan nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Menentukan tipe kompresi yang akan digunakan untuk semua konten tekstual dalam dokumen. Tulis [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Tulis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer di dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentri [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi weak. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi weak. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan



The following example shows how to convert PowerPoint to PDF with custom options. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Menginstansiasi kelas PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Mengatur kualitas Jpeg
pdfOptions->set_JpegQuality(90);
// Mengatur perilaku untuk metafile
pdfOptions->set_SaveMetafilesAsPng(true);
// Mengatur tingkat kompresi teks
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Mendefinisikan standar PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Menyimpan presentasi sebagai PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to PDF with hidden slides. 
```cpp
// Menginstansiasi kelas Presentation yang mewakili file PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Menginstansiasi kelas PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Menambahkan slide tersembunyi
pdfOptions->set_ShowHiddenSlides(true);
// Menyimpan presentasi sebagai PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to PDF with password protected PDF. 
```cpp
// Menginstansiasi objek Presentation yang mewakili file PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Mengatur kata sandi PDF dan izin akses
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Menyimpan presentasi sebagai PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 The following example shows how to convert PowerPoint to PDF with notes. 
```cpp
// Instansiasi objek Presentation yang mewakili berkas presentasi
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Mengatur Tipe dan Ukuran Slide
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Lihat Juga

* Kelas [SaveOptions](../saveoptions/)
* Kelas [IPdfOptions](../ipdfoptions/)
* Ruang nama [Aspose::Slides::Export](../)
* Pustaka [Aspose.Slides](../../)