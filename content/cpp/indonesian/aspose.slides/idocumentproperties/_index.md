---
title: IDocumentProperties
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti sebuah presentasi.
type: docs
weight: 1977
url: /id/aspose.slides/idocumentproperties/
---
## IDocumentProperties kelas

Mewakili properti sebuah presentasi.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Menghapus dan mengatur nilai default untuk semua properti builtIn. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Menghapus semua properti khusus. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Memeriksa keberadaan properti khusus dengan nama yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Mengembalikan templat aplikasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Mengembalikan versi aplikasi. Hanya baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Mengembalikan penulis presentasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Mengembalikan kategori presentasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Mengembalikan komentar presentasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Mengembalikan properti perusahaan. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Mengembalikan status konten presentasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Mengembalikan tipe konten presentasi. Baca [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Mengembalikan jumlah properti khusus yang sebenarnya ada dalam koleksi. Hanya baca **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Mengembalikan tanggal presentasi dibuat. Nilai dalam UTC. Baca [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. Hanya baca [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Menentukan jumlah slide tersembunyi dalam dokumen presentasi. Hanya baca **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Mengembalikan properti dokumen HyperlinkBase. Baca [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produsen. Produsen berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Baca **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Mengembalikan kata kunci presentasi. Baca [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Mengembalikan tanggal presentasi terakhir dicetak. Baca [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Mengembalikan nama orang terakhir yang memodifikasi presentasi. Baca [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Mengembalikan tanggal presentasi terakhir dimodifikasi. Nilai dalam UTC. Baca saja dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek [IPresentation](../ipresentation/)). Dapat diubah melalui instance [DocumentProperties](../documentproperties/) yang dikembalikan oleh metode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Lihat contoh dalam ringkasan metode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Menunjukkan apakah hyperlink dalam dokumen terbaru. Atur elemen ini ke **true** untuk menunjukkan bahwa hyperlink diperbarui. Atur ke **false** untuk menunjukkan bahwa hyperlink usang. Baca **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Mengembalikan properti manajer. Baca [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Menentukan total jumlah klip suara atau video yang ada dalam dokumen. Hanya baca **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Mengembalikan nama aplikasi. Baca [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Menentukan jumlah slide dalam presentasi yang berisi catatan. Hanya baca **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Menentukan total jumlah paragraf yang ditemukan dalam dokumen jika berlaku. Hanya baca **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Mengembalikan format yang dimaksudkan untuk presentasi. Baca [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Mengembalikan nomor revisi presentasi. Baca **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan skala thumbnail dokumen ke tampilan. Atur ke **false** untuk memotong thumbnail dokumen agar hanya menampilkan bagian yang sesuai dengan tampilan. Baca **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Menentukan apakah presentasi dibagikan antara beberapa orang. Baca **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Menentukan total jumlah slide dalam dokumen presentasi. Hanya baca **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Mengembalikan subjek presentasi. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Mengembalikan judul presentasi. Baca [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Menentukan judul setiap bagian dokumen. Bagian-bagian ini bukan bagian dokumen melainkan representasi konseptual dari bagian dokumen. Hanya baca [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Total waktu penyuntingan presentasi. Baca [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Menentukan total jumlah kata yang terdapat dalam dokumen. Hanya baca **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Mengembalikan nama properti khusus pada indeks yang ditentukan. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Mendapatkan nilai boolean bernama dari properti khusus. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Mendapatkan nilai integer bernama dari properti khusus. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Mendapatkan nilai DateTime bernama dari properti khusus. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Mendapatkan nilai string bernama dari properti khusus. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Mendapatkan nilai float bernama dari properti khusus. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Mendapatkan nilai double bernama dari properti khusus. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Mendapatkan array label sensitivitas dari properti dokumen khusus (Metadata SDK Microsoft Information Protection). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Mengembalikan properti khusus yang terkait dengan nama yang ditentukan. Baca [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Menetapkan properti khusus yang terkait dengan nama yang ditentukan. Tulis [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Menghapus properti khusus yang terkait dengan nama yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Menetapkan templat aplikasi. Tulis [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Menetapkan penulis presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Menetapkan kategori presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Menetapkan komentar presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Menetapkan properti perusahaan. Tulis [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Menetapkan status konten presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Menetapkan tipe konten presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Mengembalikan tanggal presentasi dibuat. Nilai dalam UTC. Tulis [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Menetapkan properti dokumen HyperlinkBase. Tulis [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produsen. Produsen berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Tulis **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Menetapkan kata kunci presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Mengembalikan tanggal presentasi terakhir dicetak. Tulis [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Menetapkan nama orang terakhir yang memodifikasi presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Mengembalikan tanggal presentasi terakhir dimodifikasi. Nilai dalam UTC. Baca saja dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek [IPresentation](../ipresentation/)). Dapat diubah melalui instance [DocumentProperties](../documentproperties/) yang dikembalikan oleh metode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Lihat contoh dalam ringkasan metode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Menunjukkan apakah hyperlink dalam dokumen terbaru. Atur elemen ini ke **true** untuk menunjukkan bahwa hyperlink diperbarui. Atur ke **false** untuk menunjukkan bahwa hyperlink usang. Tulis **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Menetapkan properti manajer. Tulis [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Menetapkan nama aplikasi. Tulis [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Menetapkan format yang dimaksudkan untuk presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Menetapkan nomor revisi presentasi. Tulis **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan skala thumbnail dokumen ke tampilan. Atur ke **false** untuk memotong thumbnail dokumen agar hanya menampilkan bagian yang sesuai dengan tampilan. Tulis **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Menentukan apakah presentasi dibagikan antara beberapa orang. Tulis **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Menetapkan subjek presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Menetapkan judul presentasi. Tulis [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Total waktu penyuntingan presentasi. Tulis [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Menetapkan properti khusus boolean bernama. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Menetapkan properti khusus integer bernama. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Menetapkan properti khusus DateTime bernama. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Menetapkan properti khusus string bernama. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Menetapkan properti khusus float bernama. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Menetapkan properti khusus double bernama. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruktion C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)