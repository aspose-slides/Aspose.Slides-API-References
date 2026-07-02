---
title: Table
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili tabel pada slide.
type: docs
weight: 10840
url: /id/aspose.slides/table/
---
## Kelas Table

Mewakili sebuah tabel pada slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana bentuk akan dirender dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Mengembalikan koleksi kolom. Baca-saja [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada bentuk. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus bentuk. Baca-saja [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Mengembalikan objek TableFormat.FillFormat yang berisi format isian untuk Table. Baca-saja [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Menentukan apakah kolom pertama tabel harus digambar dengan format khusus. Baca/tulis Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Menentukan apakah baris pertama tabel harus digambar dengan format khusus. Baca/tulis Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci bentuk. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi bentuk, diukur dalam point. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah bentuk disembunyikan. Baca/tulis Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Menentukan apakah baris genap harus digambar dengan format yang berbeda. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang ditetapkan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Baca-saja [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang ditetapkan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah bentuk dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah bentuk adalah TextHolder_PPT. Baca-saja Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Mengembalikan sel pada indeks kolom dan baris yang ditentukan. Baca-saja [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Menentukan apakah kolom terakhir tabel harus digambar dengan format khusus. Baca/tulis Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Menentukan apakah baris terakhir tabel harus digambar dengan format khusus. Baca/tulis Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama bentuk. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop merujuk bentuk secara andal dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Baca-saja [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Menentukan apakah tabel memiliki urutan baca kanan ke kiri. Baca/tulis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat bentuk yang ditentukan diputar di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Mengembalikan koleksi baris. Baca-saja [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci bentuk. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari bentuk. Baca-saja [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Mengambil atau mengatur gaya tabel bawaan. Baca/tulis [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini. Baca-saja [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti 3D. Baca-saja [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat dipilih kembali oleh pengguna atau secara program, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Menentukan apakah kolom genap harus digambar dengan format yang berbeda. Baca/tulis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar bentuk, diukur dalam point. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam point. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam point. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi bentuk dalam urutan z. Shapes[0] mengembalikan bentuk di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan bentuk di depan urutan z. Baca-saja Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini). Null dikembalikan jika bentuk saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail bentuk. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail bentuk. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual bentuk yang dihitung dari kontennya yang dirender. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Menggabungkan sel tetangga. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Mengatur properti format paragraf yang ditentukan ke semua paragraf sel tabel. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Mengatur properti format bagian yang ditentukan ke semua bagian sel tabel. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Mengatur properti format bingkai teks yang ditentukan ke semua bingkai teks sel tabel. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai berkas SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai berkas SVG. |

### Lihat Juga

* kelas [GraphicalObject](../graphicalobject)
* antarmuka [ITable](../itable)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->