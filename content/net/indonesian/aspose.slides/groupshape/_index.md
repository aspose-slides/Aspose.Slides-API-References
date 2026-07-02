---
title: GroupShape
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sekelompok bentuk pada slide.
type: docs
weight: 5070
url: /id/aspose.slides/groupshape/
---
## GroupShape kelas

Mewakili sekelompok bentuk pada slide.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Memungkinkan mendapatkan antarmuka IShape dasar. Hanya-baca [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana sebuah bentuk akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada bentuk. Hanya-baca Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus bentuk. Hanya-baca [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti efek. Hanya-baca [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti isi. Hanya-baca [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Mengembalikan kunci bentuk. Hanya-baca [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mendapat atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah bentuk disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Hanya-baca [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengatur opsi ‘Mark as decorative’. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah bentuk dikelompokkan. Hanya-baca Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah bentuk adalah TextHolder_PPT. Hanya-baca Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk. Catatan: Mengembalikan null untuk objek GroupShape karena mereka tidak memiliki properti garis. Hanya-baca [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama sebuah bentuk. Tidak boleh null. Gunakan string kosong bila diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop mereferensikan bentuk dengan andal dari mana saja dalam dokumen. Hanya-baca UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Hanya-baca [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari sebuah slide. Hanya-baca [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi bentuk di sekitar sumbu z. Nilai positif berarti rotasi searah jarum jam; nilai negatif berarti rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Mengembalikan kunci bentuk. Hanya-baca [`IGroupShapeLock`](../igroupshapelock). (2 properti) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Mengembalikan koleksi bentuk di dalam grup. Hanya-baca [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari sebuah bentuk. Hanya-baca [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti 3d. Hanya-baca [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain. Karena nilai ini dapat diubah oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mendapat atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mendapat atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mendapat atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi sebuah bentuk dalam urutan z. Shapes[0] mengembalikan bentuk paling belakang dalam urutan z, dan Shapes[Shapes.Count - 1] mengembalikan bentuk paling depan dalam urutan z. Hanya-baca Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau master slide yang diwarisi oleh bentuk saat ini). Mengembalikan null jika bentuk saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail bentuk. Tipe ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail bentuk. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Menentukan bahwa bentuk ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [Shape](../shape)
* antarmuka [IGroupShape](../igroupshape)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->