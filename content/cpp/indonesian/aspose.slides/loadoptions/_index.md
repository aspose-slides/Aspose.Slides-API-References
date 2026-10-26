---
title: LoadOptions
second_title: Aspose.Slides untuk Referensi API C++
description: Memungkinkan menentukan opsi tambahan (seperti format atau font default) saat memuat sebuah presentasi.
type: docs
weight: 4395
url: /id/aspose.slides/loadoptions/
---
## LoadOptions kelas

Memungkinkan untuk menentukan opsi tambahan (seperti format atau font default) saat memuat sebuah presentasi.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs dalam memori. Opsi-opsi ini dimaksudkan untuk mengatur rasio kinerja/konsumsi memori terbaik untuk lingkungan atau persyaratan tertentu. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | Mengembalikan font Asia yang digunakan jika font sumber tidak ditemukan. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | Mengembalikan font Reguler yang digunakan jika font sumber tidak ditemukan. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | Mengembalikan font Simbol yang digunakan jika font sumber tidak ditemukan. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | Mengembalikan bahasa default untuk teks presentasi. Baca [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | Menentukan apakah [Aspose.Slides](../) akan menghapus semua objek biner yang tertanam saat memuat presentasi. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font-font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lainnya |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | Token untuk memantau permintaan interupsi. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Mengembalikan format presentasi yang akan dimuat. Baca [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | Properti ini masuk akal jika file presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi terenkripsi harus dimuat dengan menggunakan kata sandi yang benar. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari file terenkripsi tidak publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Baca **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Mendapatkan kata sandi. Baca [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | Mengembalikan antarmuka callback yang mengelola pemuatan sumber daya eksternal. Baca [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | Mendapatkan opsi untuk spreadsheet. Misalnya, opsi ini memengaruhi perhitungan rumus untuk diagram. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | Mengembalikan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dihentikan. Baca [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
|  [LoadOptions](./loadoptions/)() | Membuat opsi pemuatan default baru. |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | Membuat opsi pemuatan baru. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs dalam memori. Opsi-opsi ini dimaksudkan untuk mengatur rasio kinerja/konsumsi memori terbaik untuk lingkungan atau persyaratan tertentu. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | Menetapkan font Asia yang digunakan jika font sumber tidak ditemukan. Tulis [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | Menetapkan font Reguler yang digunakan jika font sumber tidak ditemukan. Tulis [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | Menetapkan font Simbol yang digunakan jika font sumber tidak ditemukan. Tulis [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | Menetapkan bahasa default untuk teks presentasi. Tulis [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | Menentukan apakah [Aspose.Slides](../) akan menghapus semua objek biner yang tertanam saat memuat presentasi. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font-font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lainnya |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | Token untuk memantau permintaan interupsi. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | Menetapkan format presentasi yang akan dimuat. Tulis [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | Properti ini masuk akal jika file presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi terenkripsi harus dimuat dengan menggunakan kata sandi yang benar. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari file terenkripsi tidak publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Tulis **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Menetapkan kata sandi. Tulis [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | Menetapkan antarmuka callback yang mengelola pemuatan sumber daya eksternal. Tulis [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | Mendapatkan opsi untuk spreadsheet. Misalnya, opsi ini memengaruhi perhitungan rumus untuk diagram. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Menetapkan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dihentikan. Tulis [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ILoadOptions](../iloadoptions/)
* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)