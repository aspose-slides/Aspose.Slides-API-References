---
title: IDocumentProperties
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili properti presentasi.
type: docs
weight: 5690
url: /id/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Mewakili properti dari sebuah presentasi.

```csharp
public interface IDocumentProperties
```

## Properties

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Mengembalikan atau mengatur templat aplikasi. Baca/tulis String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Mengembalikan versi aplikasi. Baca-saja String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Mengembalikan atau mengatur penulis presentasi. Baca/tulis String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Mengembalikan atau mengatur kategori presentasi. Baca/tulis String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Mengembalikan atau mengatur komentar presentasi. Baca/tulis String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Mengembalikan atau mengatur properti perusahaan. Baca/tulis String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Mengembalikan atau mengatur status konten presentasi. Baca/tulis String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Mengembalikan atau mengatur tipe konten presentasi. Baca/tulis String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Mengembalikan jumlah properti khusus yang sebenarnya ada dalam koleksi. Baca-saja Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. Baca/tulis DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. Baca-saja IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Menentukan jumlah slide tersembunyi dalam dokumen presentasi. Baca-saja Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Mengembalikan atau mengatur properti dokumen HyperlinkBase. Baca/tulis String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini hanya diperbarui dalam bagian ini oleh produsen. Produsen berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Baca/tulis Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Mengembalikan atau mengatur properti khusus yang terkait dengan nama tertentu. Baca/tulis Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Mengembalikan atau mengatur kata kunci presentasi. Baca/tulis String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Mengembalikan tanggal saat presentasi terakhir dicetak. Baca/tulis DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. Baca/tulis String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Mengembalikan tanggal terakhir presentasi dimodifikasi. Nilai dalam UTC.P Baca-saja pada kasus Presentation.DocumentProperties (karena akan diperbarui secara internal saat proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Lihat contoh dalam ringkasan metode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Menunjukkan apakah hyperlink dalam dokumen sudah up-to-date. Atur elemen ini ke **true** untuk menunjukkan bahwa hyperlink diperbarui. Atur elemen ini ke **false** untuk menunjukkan bahwa hyperlink sudah usang. Baca/tulis Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Mengembalikan atau mengatur properti manajer. Baca/tulis String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Menentukan total jumlah klip suara atau video yang ada dalam dokumen. Baca-saja Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Mengembalikan atau mengatur nama aplikasi. Baca/tulis String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Menentukan jumlah slide dalam presentasi yang berisi catatan. Baca-saja Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Menentukan total jumlah paragraf yang ditemukan dalam dokumen bila berlaku. Baca-saja Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Mengembalikan atau mengatur format yang dimaksudkan untuk presentasi. Baca/tulis String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Mengembalikan atau mengatur nomor revisi presentasi. Baca/tulis Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan penskalaan thumbnail dokumen ke tampilan. Atur ke **false** untuk mengaktifkan pemotongan thumbnail dokumen agar hanya menampilkan bagian yang cocok dengan tampilan. Baca/tulis Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Menentukan apakah presentasi dibagikan di antara banyak orang. Baca/tulis Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Menentukan total jumlah slide dalam dokumen presentasi. Baca-saja Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Mengembalikan atau mengatur subjek presentasi. Baca/tulis String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Mengembalikan atau mengatur judul presentasi. Baca/tulis String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Menentukan judul setiap bagian dokumen. Bagian ini bukan bagian dokumen melainkan representasi konseptual dari seksi dokumen. Baca-saja string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Total waktu penyuntingan presentasi. Baca/tulis TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Menentukan total jumlah kata yang terdapat dalam dokumen. Baca-saja Int32. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Menghapus dan mengatur nilai default untuk semua properti builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Menghapus semua properti khusus. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Memeriksa keberadaan properti khusus dengan nama tertentu. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Mengembalikan nama properti khusus pada indeks yang ditentukan. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Mendapatkan nilai boolean bernama dari properti khusus. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Mendapatkan nilai DateTime bernama dari properti khusus. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Mendapatkan nilai double bernama dari properti khusus. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Mendapatkan nilai float bernama dari properti khusus. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Mendapatkan nilai integer bernama dari properti khusus. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Mendapatkan nilai string bernama dari properti khusus. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Mendapatkan array label sensitivitas dari properti dokumen khusus (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Menghapus properti khusus yang terkait dengan nama tertentu. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Menetapkan properti khusus boolean bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Menetapkan properti khusus DateTime bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Menetapkan properti khusus double bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Menetapkan properti khusus float bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Menetapkan properti khusus integer bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Menetapkan properti khusus string bernama. |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->