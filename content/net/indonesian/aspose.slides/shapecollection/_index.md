---
title: ShapeCollection
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili kumpulan bentuk.
type: docs
weight: 9860
url: /id/aspose.slides/shapecollection/
---
## ShapeCollection kelas

Mewakili kumpulan bentuk.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya-baca Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Mendapatkan objek grup bentuk induk untuk koleksi bentuk. Hanya-baca [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Mengembalikan akar sinkronisasi. Hanya-baca Object. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi bentuk. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi bentuk menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Membuat bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi bentuk. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi bentuk. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi bentuk. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Membuat auto shape baru dan menambahkannya ke akhir koleksi bentuk, dengan opsional menginisialisasinya dengan format templat default. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Shape yang digandakan mempertahankan posisi dan ukuran aslinya. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Shape baru mempertahankan lebar dan tinggi dari *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Membuat connector shape baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Membuat connector shape baru dan menambahkannya ke akhir koleksi bentuk, dengan opsional menerapkan gaya templat default. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi bentuk. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individual, dan menambahkan grup yang dihasilkan ke akhir koleksi bentuk. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi bentuk. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Membuat bingkai Section Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Membuat tabel baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Menghapus semua shape dari koleksi bentuk. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Mengembalikan enumerator yang mengiterasi koleksi. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Mengembalikan indeks berbasis nol dari kemunculan pertama shape yang ditentukan dalam koleksi. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan format templat default. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan opsional menginisialisasinya dengan gaya templat default. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Membuat chart baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Membuat salinan dari shape yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Shape yang digandakan mempertahankan posisi dan ukuran aslinya. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Membuat salinan dari shape yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Shape baru mempertahankan lebar dan tinggi dari *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Membuat salinan dari shape yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Membuat connector shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan gaya templat default. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Membuat connector shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan opsional menerapkan gaya templat default. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Membuat grup shape kosong baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Membuat bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Membuat tabel baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Membuat bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Menghapus kemunculan pertama shape yang ditentukan dari koleksi bentuk. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Menghapus shape pada indeks yang ditentukan dari koleksi bentuk. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Memindahkan shape yang ditentukan ke posisi baru dalam koleksi bentuk. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Memindahkan shape yang ditentukan dalam koleksi bentuk, menempatkannya mulai dari indeks yang diberikan. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Membuat dan mengembalikan array yang berisi semua shape. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Membuat dan mengembalikan array yang berisi semua shape dalam rentang yang ditentukan. |

### Lihat Juga

* kelas [DomObject&lt;TParent&gt;](../domobject-1)
* kelas [GroupShape](../groupshape)
* antarmuka [IShapeCollection](../ishapecollection)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->