---
title: IShapeCollection
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili kumpulan bentuk.
type: docs
weight: 6960
url: /id/aspose.slides/ishapecollection/
---
## Antarmuka IShapeCollection

Mewakili kumpulan bentuk.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Mendapatkan objek bentuk grup induk untuk koleksi bentuk. Hanya-baca [`IGroupShape`](../igroupshape). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi bentuk. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi bentuk menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Membuat bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi bentuk. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi bentuk. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi bentuk. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Membuat auto shape baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menginisialisasinya dengan format templat default. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk yang digandakan mempertahankan posisi dan ukuran aslinya. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk baru mempertahankan lebar dan tinggi dari *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Membuat bentuk penghubung baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Membuat bentuk penghubung baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menerapkan gaya templat default. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Membuat grup bentuk kosong baru dan menambahkannya ke akhir koleksi bentuk. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua bentuk yang ditambahkan. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Membuat grup bentuk baru, mengonversi gambar SVG yang ditentukan menjadi bentuk-bentuk individual, dan menambahkan grup yang dihasilkan ke akhir koleksi bentuk. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Membuat auto shape persegi panjang baru untuk menampung konten matematis dan menambahkannya ke akhir koleksi bentuk. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Membuat bingkai Section Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Membuat tabel baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Menghapus semua bentuk dari koleksi bentuk. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Mengembalikan indeks berbasis nol dari kemunculan pertama bentuk yang ditentukan dalam koleksi. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan format templat default. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya templat default. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Membuat grafik baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk yang digandakan mempertahankan posisi dan ukuran aslinya. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk baru mempertahankan lebar dan tinggi dari *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan gaya templat default. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menerapkan gaya templat default. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Membuat grup bentuk kosong baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua bentuk yang ditambahkan. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Membuat bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Membuat tabel baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Membuat bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Menghapus kemunculan pertama bentuk yang ditentukan dari koleksi bentuk. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Menghapus bentuk pada indeks yang ditentukan dari koleksi bentuk. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Memindahkan bentuk yang ditentukan ke posisi baru dalam koleksi bentuk. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Memindahkan bentuk-bentuk yang ditentukan dalam koleksi bentuk, menempatkannya mulai dari indeks yang diberikan. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Membuat dan mengembalikan array yang berisi semua bentuk. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Membuat dan mengembalikan array yang berisi semua bentuk dalam rentang yang ditentukan. |

### Lihat Juga

* antarmuka [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* antarmuka [IShape](../ishape)
* ruangnama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->