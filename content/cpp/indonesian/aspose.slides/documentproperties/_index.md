---
title: DocumentProperties
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti sebuah presentasi.
type: docs
weight: 794
url: /id/aspose.slides/documentproperties/
---
## DocumentProperties kelas

Mewakili properti dari sebuah presentasi.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Membersihkan dan menetapkan nilai default untuk semua properti builtIn. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Menghapus semua properti khusus. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Menggandakan objek saat ini |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Menggandakan objek saat ini |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Memeriksa keberadaan properti khusus dengan nama yang ditentukan. |
| [DocumentProperties](./documentproperties/)() | Menginisialisasi instance baru kelas [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Mengembalikan templat aplikasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Mengembalikan versi aplikasi. Hanya-baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Mengembalikan penulis presentasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Mengembalikan kategori presentasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Mengembalikan komentar presentasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Mengembalikan properti perusahaan. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Mengembalikan status konten presentasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Mengembalikan tipe konten presentasi. Baca [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Mengembalikan jumlah properti khusus yang sebenarnya terdapat dalam koleksi. Hanya-baca **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. Baca [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian di setiap grup. Hanya-baca [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Mengembalikan jumlah slide tersembunyi dalam dokumen presentasi. Hanya-baca **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Mengembalikan properti dokumen HyperlinkBase. Baca [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produser. Produser berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Baca **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Mengembalikan kata kunci presentasi. Baca [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Mengembalikan tanggal ketika presentasi terakhir kali dicetak. Baca [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Mengembalikan nama orang terakhir yang mengubah presentasi. Baca [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Mengembalikan tanggal presentasi terakhir diubah. Nilai dalam UTC. Hanya-baca bila [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (karena akan diperbarui secara internal selama proses penyimpanan objek [IPresentation](../ipresentation/)). Dapat diubah melalui instance [DocumentProperties](./) yang dikembalikan oleh metode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Lihat contoh dalam ringkasan metode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Menunjukkan apakah hyperlink dalam dokumen mutakhir. Setel elemen ini ke **true** untuk menandakan hyperlink telah diperbarui. Setel ke **false** untuk menandakan hyperlink sudah kedaluwarsa. Baca **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Mengembalikan properti manajer. Baca [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Mengembalikan total jumlah klip suara atau video yang ada dalam dokumen. Hanya-baca **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Mengembalikan nama aplikasi. Baca [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Mengembalikan jumlah slide dalam presentasi yang berisi catatan. Hanya-baca **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Mengembalikan total jumlah paragraf yang ditemukan dalam dokumen bila berlaku. Hanya-baca **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Mengembalikan format yang dimaksudkan untuk presentasi. Baca [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Mengembalikan nomor revisi presentasi. Baca **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Menunjukkan mode tampilan thumbnail dokumen. Setel elemen ini ke **true** untuk mengaktifkan skala thumbnail dokumen ke tampilan. Setel ke **false** untuk memotong thumbnail dokumen agar hanya menampilkan bagian yang sesuai dengan tampilan. Baca **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Menentukan apakah presentasi dibagikan di antara beberapa orang. Baca **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Mengembalikan total jumlah slide dalam dokumen presentasi. Hanya-baca **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Mengembalikan subjek presentasi. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Mengembalikan judul presentasi. Baca [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Menentukan judul setiap bagian dokumen. Bagian-bagian ini bukan bagian dokumen melainkan representasi konseptual dari bagian dokumen. Hanya-baca [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Total waktu penyuntingan presentasi. Baca [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Mengembalikan total jumlah kata dalam dokumen. Hanya-baca **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Mengembalikan nama properti khusus pada indeks yang ditentukan. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Mendapatkan nilai boolean bernama dari properti khusus. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Mendapatkan nilai integer bernama dari properti khusus. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Mendapatkan nilai DateTime bernama dari properti khusus. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Mendapatkan nilai string bernama dari properti khusus. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Mendapatkan nilai float bernama dari properti khusus. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Mendapatkan nilai double bernama dari properti khusus. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Mendapatkan array label sensitivitas dari properti dokumen khusus (Metadata Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Mengembalikan properti khusus yang terkait dengan nama yang ditentukan. Baca [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Menetapkan properti khusus yang terkait dengan nama yang ditentukan. Tulis [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Menghapus properti khusus yang terkait dengan nama yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Menetapkan templat aplikasi. Tulis [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Menetapkan penulis presentasi. Tulis [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Menetapkan kategori presentasi. Tulis [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Menetapkan komentar presentasi. Tulis [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Menetapkan properti perusahaan. Tulis [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Menetapkan status konten presentasi. Tulis [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Menetapkan tipe konten presentasi. Tulis [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. Tulis [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Menetapkan properti dokumen HyperlinkBase. Tulis [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produser. Produser berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Tulis **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Menetapkan kata kunci presentasi. Tulis [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Mengembalikan tanggal saat presentasi terakhir dicetak. Tulis [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Menetapkan nama orang terakhir yang mengubah presentasi. Tulis [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Mengembalikan tanggal presentasi terakhir diubah. Nilai dalam UTC. Hanya-baca bila [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (karena akan diperbarui secara internal selama proses penyimpanan objek [IPresentation](../ipresentation/)). Dapat diubah melalui instance [DocumentProperties](./) yang dikembalikan oleh metode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Lihat contoh dalam ringkasan metode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Menunjukkan apakah hyperlink dalam dokumen mutakhir. Setel elemen ini ke **true** untuk menandakan hyperlink telah diperbarui. Setel ke **false** untuk menandakan hyperlink sudah kedaluwarsa. Tulis **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Menetapkan properti manajer. Tulis [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Menetapkan nama aplikasi. Tulis [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Menetapkan format yang dimaksudkan untuk presentasi. Tulis [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Menetapkan nomor revisi presentasi. Tulis **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Menunjukkan mode tampilan thumbnail dokumen. Setel elemen ini ke **true** untuk mengaktifkan skala thumbnail dokumen ke tampilan. Setel ke **false** untuk memotong thumbnail dokumen agar hanya menampilkan bagian yang sesuai dengan tampilan. Tulis **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Menentukan apakah presentasi dibagikan di antara beberapa orang. Tulis **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Menetapkan subjek presentasi. Tulis [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Menetapkan judul presentasi. Tulis [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Total waktu penyuntingan presentasi. Tulis [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Menetapkan properti khusus boolean bernama. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Menetapkan properti khusus integer bernama. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Menetapkan properti khusus DateTime bernama. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Menetapkan properti khusus string bernama. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Menetapkan properti khusus float bernama. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Menetapkan properti khusus double bernama. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

Contoh berikut menunjukkan cara mengakses Properti bawaan PowerPoint [Presentation](../presentation/).
```cpp
// Membuat instance kelas Presentation yang mewakili presentasi
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Contoh berikut menunjukkan cara memodifikasi Properti bawaan PowerPoint [Presentation](../presentation/).
```cpp
// Membuat instance kelas Presentation yang mewakili Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Menetapkan properti bawaan
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Menyimpan presentasi Anda ke file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IDocumentProperties](../idocumentproperties/)
* Kelas [IGenericCloneable](../igenericcloneable/)
* Ruang Nama [Aspose::Slides](../)
* Library [Aspose.Slides](../../)