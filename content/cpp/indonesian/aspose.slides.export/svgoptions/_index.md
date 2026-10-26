---
title: SVGOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili opsi SVG.
type: docs
weight: 703
url: /id/aspose.slides.export/svgoptions/
---
## SVGOptions kelas

Mewakili opsi SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
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
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Mengembalikan pengaturan default. Hanya-baca [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Mengembalikan font yang digunakan bila font sumber tidak ditemukan. Membaca [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Menentukan apakah teks 3D dinonaktifkan dalam SVG. Membaca **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Membaca **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. [Aspose.Slides](../../aspose.slides/) mesin penulisan SVG memiliki solusi untuk masalah itu: memotong ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan penanda. Opsi ini mematikan perilaku tersebut. Membaca **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Menentukan cara menangani font yang dimuat secara eksternal. Membaca [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Mengembalikan gaya visual gradien. Membaca [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Menyediakan opsi yang mengontrol tampilan objek [Ink](../../aspose.slides.ink/) dalam dokumen yang diekspor. Hanya-baca [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Menentukan kualitas enkoding JPEG. Membaca **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Mengembalikan batas resolusi rendah untuk rasterisasi metafile. Membaca **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Mewakili tingkat kompresi gambar |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Mengembalikan dan menyetel antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. Membaca [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Mengembalikan pengaturan untuk pembuatan file SVG yang paling sederhana dan terkecil. Hanya-baca [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Membaca **bool**. Nilai default adalah **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Menentukan apakah melakukan rotasi spesifik pada bentuk saat merender atau tidak. Membaca **bool**. Nilai default adalah true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Menentukan apakah bingkai teks akan dimasukkan dalam area render atau tidak. Membaca **bool**. Nilai default adalah false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Menentukan apakah teks pada slide akan disimpan sebagai grafik. Membaca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Mengembalikan atau menyetel objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Membaca [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Mengembalikan pengaturan untuk pembuatan file SVG yang paling akurat. Hanya-baca [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa-apa, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa-apa, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Menetapkan font yang digunakan bila font sumber tidak ditemukan. Menulis [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Menentukan apakah teks 3D dinonaktifkan dalam SVG. Menulis **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Menetapkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Menulis **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. [Aspose.Slides](../../aspose.slides/) mesin penulisan SVG memiliki solusi untuk masalah itu: memotong ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan penanda. Opsi ini mematikan perilaku tersebut. Menulis **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Menentukan cara menangani font yang dimuat secara eksternal. Menulis [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Menetapkan gaya visual gradien. Menulis [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Menentukan kualitas enkoding JPEG. Menulis **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Menetapkan batas resolusi rendah untuk rasterisasi metafile. Menulis **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Mewakili tingkat kompresi gambar |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase. Lihat [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Mengembalikan dan menyetel antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. Menulis [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Menulis **bool**. Nilai default adalah **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Menentukan apakah melakukan rotasi spesifik pada bentuk saat merender atau tidak. Menulis **bool**. Nilai default adalah true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Menentukan apakah bingkai teks akan dimasukkan dalam area render atau tidak. Menulis **bool**. Nilai default adalah false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Menentukan apakah teks pada slide akan disimpan sebagai grafik. Menulis **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Mengembalikan atau menyetel objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Menulis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Menginisialisasi instansi baru dari kelas [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Menginisialisasi instansi baru dari kelas [SVGOptions](./) dengan menentukan objek kontroler penanaman tautan. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruktor C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [SaveOptions](../saveoptions/)
* Kelas [ISVGOptions](../isvgoptions/)
* Ruang nama [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)