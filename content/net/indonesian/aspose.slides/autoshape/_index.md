---
title: AutoShape
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili sebuah AutoShape.
type: docs
weight: 880
url: /id/aspose.slides/autoshape/
---
## Kelas AutoShape

Mewakili sebuah AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Mengembalikan koleksi nilai penyesuaian shape. Hanya-baca [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Mengembalikan kunci autoshape. Hanya-baca [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Hanya-baca Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data kustom shape. Hanya-baca [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti efek. Hanya-baca [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format pengisian untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti pengisian. Hanya-baca [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai shape. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi shape, diukur dalam point. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape tersembunyi. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan pengelola hyperlink. Hanya-baca [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Mark as decorative'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Hanya-baca Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Menentukan apakah shape adalah kotak teks. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Hanya-baca Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti garis. Hanya-baca [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Tidak boleh null. Gunakan string kosong bila diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen. Hanya-baca UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Hanya-baca [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Hanya-baca [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai shape mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat shape yang ditentukan diputar pada sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Mengembalikan kunci shape. Hanya-baca [`IAutoShapeLock`](../iautoshapelock). (2 properti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Mengembalikan objek gaya shape. Hanya-baca [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Mengembalikan atau mengatur tipe preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default mereka. Baca/tulis [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari shape. Hanya-baca [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Mengembalikan objek TextFrame untuk AutoShape. Hanya-baca [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti 3d. Hanya-baca [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain. Karena nilai ini dapat dipindahtugaskan oleh pengguna atau secara programatis, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh style atau format pengisian. Baca/tulis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar shape, diukur dalam point. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam point. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam point. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Hanya-baca Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Menambahkan TextFrame baru ke shape. Jika shape sudah memiliki TextFrame maka hanya mengubah teksnya. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Membuat dan mengembalikan array elemen shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Memperbarui geometri shape dari objek [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Memperbarui geometri shape dari array [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [GeometryShape](../geometryshape)
* antarmuka [IAutoShape](../iautoshape)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->