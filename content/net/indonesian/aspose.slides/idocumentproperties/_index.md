---
title: IDocumentProperties
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili properti sebuah presentasi.
type: docs
weight: 5730
url: /id/aspose.slides/idocumentproperties/
---
## IDocumentProperties antarmuka

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Properti

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Mengembalikan atau mengatur templat aplikasi. Read/write String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Mengembalikan versi aplikasi. Read-only String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Mengembalikan atau mengatur penulis presentasi. Read/write String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Mengembalikan atau mengatur kategori presentasi. Read/write String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Mengembalikan atau mengatur komentar presentasi. Read/write String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Mengembalikan atau mengatur properti perusahaan. Read/write String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Mengembalikan atau mengatur status konten presentasi. Read/write String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Mengembalikan atau mengatur tipe konten presentasi. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Mengembalikan jumlah properti kustom yang sebenarnya terdapat dalam koleksi. Read-only Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Mengembalikan tanggal pembuatan presentasi. Nilai berada dalam UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Menentukan jumlah slide tersembunyi dalam dokumen presentasi. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Mengembalikan atau mengatur properti dokumen HyperlinkBase. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Menentukan bahwa satu atau lebih hyperlink di bagian ini diperbarui secara eksklusif di bagian ini oleh produsen. Produsen berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan di bagian ini. Read/write Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Mengembalikan atau mengatur properti kustom yang terkait dengan nama tertentu. Read/write Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Mengembalikan atau mengatur kata kunci presentasi. Read/write String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Mengembalikan tanggal saat presentasi terakhir dicetak. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. Read/write String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Mengembalikan tanggal terakhir presentasi dimodifikasi. Nilai berada dalam UTC. Read-only dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Lihat contoh di ringkasan metode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Menunjukkan apakah hyperlink dalam dokumen sudah terbaru. Atur elemen ini ke **true** untuk menandakan bahwa hyperlink telah diperbarui. Atur elemen ini ke **false** untuk menandakan bahwa hyperlink sudah usang. Read/write Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Mengembalikan atau mengatur properti manajer. Read/write String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Menentukan total jumlah klip suara atau video yang ada dalam dokumen. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Mengembalikan atau mengatur nama aplikasi. Read/write String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Menentukan jumlah slide dalam presentasi yang berisi catatan. Read-only Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Menentukan total jumlah paragraf yang ditemukan dalam dokumen jika berlaku. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Mengembalikan atau mengatur format yang dimaksudkan untuk presentasi. Read/write String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Mengembalikan atau mengatur nomor revisi presentasi. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan skala thumbnail dokumen ke tampilan. Atur elemen ini ke **false** untuk mengaktifkan pemotongan thumbnail dokumen agar hanya menampilkan bagian yang sesuai dengan tampilan. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Menentukan apakah presentasi dibagikan di antara beberapa orang. Read/write Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Menentukan total jumlah slide dalam dokumen presentasi. Read-only Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Mengembalikan atau mengatur subjek presentasi. Read/write String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Mengembalikan atau mengatur judul presentasi. Read/write String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Menentukan judul setiap bagian dokumen. Bagian-bagian ini bukan bagian dokumen melainkan representasi konseptual dari bagian dokumen. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Total waktu penyuntingan presentasi. Read/write TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Menentukan total jumlah kata yang terdapat dalam dokumen. Read-only Int32. |

## Metode

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Menghapus dan mengatur nilai default untuk semua properti builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Menghapus semua properti kustom. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Memeriksa keberadaan properti kustom dengan nama tertentu. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Mengembalikan nama properti kustom pada indeks yang ditentukan. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Mendapatkan nilai boolean bernama dari properti kustom. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Mendapatkan nilai DateTime bernama dari properti kustom. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Mendapatkan nilai double bernama dari properti kustom. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Mendapatkan nilai float bernama dari properti kustom. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Mendapatkan nilai integer bernama dari properti kustom. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Mendapatkan nilai string bernama dari properti kustom. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Mendapatkan array label sensitivitas dari properti dokumen kustom (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Menghapus properti kustom yang terkait dengan nama tertentu. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Mengatur properti kustom boolean bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Mengatur properti kustom DateTime bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Mengatur properti kustom double bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Mengatur properti kustom float bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Mengatur properti kustom integer bernama. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Mengatur properti kustom string bernama. |

### Lihat Juga

* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->