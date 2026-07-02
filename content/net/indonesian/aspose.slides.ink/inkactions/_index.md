---
title: InkActions
second_title: Aspose.Sildes for .NET Referensi API
description: Mewakili akar dari aksi tinta.
type: docs
weight: 7540
url: /id/aspose.slides.ink/inkactions/
---
## InkActions kelas

Mewakili akar dari aksi tinta.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana sebuah shape akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah titik koneksi pada shape. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data kustom shape. Baca-saja [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format pengisian untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti pengisian. Baca-saja [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi shape, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Baca-saja [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Mark as decorative'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Baca-saja Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama sebuah shape. Tidak boleh null. Gunakan string kosong jika diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik yang berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape dengan andal dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk sebuah shape. Mengembalikan null jika shape tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Baca-saja [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari sebuah shape. Baca-saja [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3D. Baca-saja [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lainnya. Karena nilai ini dapat dipindahtugaskan oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar shape, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi sebuah shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Baca-saja Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai berkas SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai berkas SVG. |

### Lihat Juga

* kelas [GraphicalObject](../../aspose.slides/graphicalobject)
* antarmuka [IInkActions](../iinkactions)
* ruang nama [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->