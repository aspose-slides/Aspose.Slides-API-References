---
title: Shape
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sebuah shape pada slide.
type: docs
weight: 9810
url: /id/aspose.slides/shape/
---
## Shape kelas

Mewakili sebuah shape pada slide.

```csharp
public class Shape : IShape
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana sebuah shape akan dirender dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus shape. Baca-saja [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti pemformatan isian untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti isian. Baca-saja [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi shape, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan pengelola hyperlink. Baca-saja [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Mark as decorative'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Baca-saja Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama sebuah shape. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan identifier unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop untuk secara andal merujuk shape dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk sebuah shape. Mengembalikan null jika shape tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Baca-saja [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Mengembalikan kunci shape. Baca-saja [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari sebuah shape. Baca-saja [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti 3d. Baca-saja [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan identifier internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan kembali oleh pengguna atau secara programatik, ia tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar shape, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi sebuah shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Baca-saja Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Mengembalikan thumbnail shape. Tipe shape thumbnail bounds ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* antarmuka [IShape](../ishape)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->