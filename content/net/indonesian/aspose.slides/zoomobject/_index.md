---
title: ZoomObject
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili objek Zoom dalam slide.
type: docs
weight: 11850
url: /id/aspose.slides/zoomobject/
---
## ZoomObject kelas

Mewakili objek Zoom dalam slide.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus shape. Baca-saja [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek pixel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format isi untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti isi. Baca-saja [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mendapatkan atau mengatur tinggi shape, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape tersembunyi. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Baca-saja [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Mendapatkan atau mengatur tipe gambar dari objek zoom. Baca/tulis [`ZoomImageType`](../zoomimagetype). Nilai default: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mendapatkan atau mengatur opsi 'Mark as decorative'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Baca-saja Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Harus tidak null. Gunakan nilai string kosong bila diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape dengan andal dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk slide. Baca-saja [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Mendapatkan atau mengatur perilaku navigasi dalam slideshow. Baca/tulis Boolean. Nilai default: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi shape tertentu di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properti) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca/tulis Boolean. Nilai default: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk shape. Baca-saja [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3d. Baca-saja [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. Baca/tulis Single. Nilai default: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mendapatkan atau mengatur lebar shape, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mendapatkan atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mendapatkan atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Baca/tulis Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Mendapatkan atau mengatur gambar untuk objek zoom. Baca/tulis [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape paling belakang dalam urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape paling depan dalam urutan z. Baca-saja Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe bounds ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mendapatkan batas visual shape yang dihitung dari kontennya yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [GraphicalObject](../graphicalobject)
* antarmuka [IZoomObject](../izoomobject)
* ruangnama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->