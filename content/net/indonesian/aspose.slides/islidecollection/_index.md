---
title: ISlideCollection
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili koleksi slide.
type: docs
weight: 7030
url: /id/aspose.slides/islidecollection/
---
## ISlideCollection antarmuka

Mewakili koleksi slide.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [`ISlide`](../islide). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout adalah true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout adalah false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Menambahkan slide kosong baru ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Menyisipkan salinan slide sumber yang ditentukan ke posisi tertentu dalam koleksi. Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka tata letak slide sumber akan digandakan (jika allowCloneMissingLayout adalah true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout adalah false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Memindahkan slide dari koleksi ke posisi yang ditentukan. Slide akan ditempatkan mulai dari indeks dengan urutan mereka muncul dalam daftar. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Membuat dan mengembalikan array yang berisi semua slide. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Membuat dan mengembalikan array yang berisi semua slide dari rentang yang ditentukan. |

### Lihat Juga

* antarmuka [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* antarmuka [ISlide](../islide)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->