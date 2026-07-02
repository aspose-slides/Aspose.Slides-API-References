---
title: SlideCollection
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili koleksi slide.
type: docs
weight: 9950
url: /id/aspose.slides/slidecollection/
---
## SlideCollection kelas

Mewakili koleksi slide.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Mengambil jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya baca Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya baca Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Mengambil elemen pada indeks yang ditentukan. Hanya baca [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Mengembalikan akar sinkronisasi. Hanya baca Object. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Menambahkan salinan slide tertentu ke akhir koleksi. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Menambahkan salinan slide tertentu ke akhir koleksi. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Menambahkan salinan slide tertentu ke akhir bagian yang ditentukan. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Menambahkan slide kosong baru ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor pdf. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Mengembalikan enumerator yang mengiterasi koleksi. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai, maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout bernilai true) atau PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks sesuai urutan kemunculannya dalam daftar. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Membuat dan mengembalikan array yang berisi semua slide. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Membuat dan mengembalikan array yang berisi semua slide dari rentang yang ditentukan. Indeks slide pertama yang akan ditambahkan. Jumlah slide yang akan ditambahkan. |

### Lihat Juga

* kelas [DomObject&lt;TParent&gt;](../domobject-1)
* kelas [Presentation](../presentation)
* antarmuka [ISlideCollection](../islidecollection)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->