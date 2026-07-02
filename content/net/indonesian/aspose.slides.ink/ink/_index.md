---
title: Ink
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili objek tinta pada slide.
type: docs
weight: 7530
url: /id/aspose.slides.ink/ink/
---
## Kelas Ink

Mewakili objek tinta pada slide.

```csharp
public class Ink : GraphicalObject, IInk
```

## Properti

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada bentuk. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus bentuk. Baca-saja [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format isi untuk bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti isi. Baca-saja [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci bentuk. Baca-saja [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah bentuk disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan pengelola hyperlink. Baca-saja [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk gerakan mouse di atas. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah bentuk dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah bentuk adalah TextHolder_PPT. Baca-saja Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama bentuk. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik yang berskala slide dan tetap konstan selama masa bentuk serta memungkinkan PowerPoint atau kode interop mereferensikan bentuk dengan andal dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Baca-saja [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat bentuk yang ditentukan diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci bentuk. Baca-saja [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari bentuk. Baca-saja [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk bentuk. Catatan: dapat mengembalikan null untuk jenis bentuk tertentu yang tidak memiliki properti 3d. Baca-saja [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Mengambil semua jejak yang terdapat dalam elemen IInk [`IInkTrace`](../iinktrace). Baca-saja. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lainnya. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi bentuk dalam urutan z. Shapes[0] mengembalikan bentuk di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan bentuk di depan urutan z. Baca-saja Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Mengambil koleksi gambar kustom yang digunakan untuk mensimulasikan efek visual untuk kuas tinta. Gambar-gambar ini digunakan saat merender tinta dengan nilai [`InkEffectType`](../inkeffecttype) tertentu, seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengontrol bagaimana setiap efek tinta muncul. |

## Metode

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini). Null dikembalikan jika bentuk saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail bentuk. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail bentuk. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual bentuk yang dihitung dari kontennya yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [GraphicalObject](../../aspose.slides/graphicalobject)
* antarmuka [IInk](../iink)
* namespace [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->