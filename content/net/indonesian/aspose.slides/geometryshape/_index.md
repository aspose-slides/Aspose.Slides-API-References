---
title: GeometryShape
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili kelas induk untuk semua bentuk geometris.
type: docs
weight: 4950
url: /id/aspose.slides/geometryshape/
---
## GeometryShape kelas

Mewakili kelas induk untuk semua bentuk geometris.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Mengembalikan koleksi nilai penyesuaian bentuk. Hanya-baca [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah titik koneksi pada bentuk. Hanya-baca Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus bentuk. Hanya-baca [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti efek. Hanya-baca [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format isian untuk bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti isian. Hanya-baca [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah bentuk disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Hanya-baca [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah bentuk dikelompokkan. Hanya-baca Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah bentuk adalah TextHolder_PPT. Hanya-baca Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti garis. Hanya-baca [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama bentuk. Tidak boleh null. Gunakan nilai string kosong bila diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengenal unik berskala slide yang tetap konstan selama umur bentuk dan memungkinkan PowerPoint atau kode interop merujuk bentuk secara andal dari mana saja dalam dokumen. Hanya-baca UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Hanya-baca [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Hanya-baca [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi bentuk yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Mengembalikan kunci bentuk. Hanya-baca [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Mengembalikan objek gaya bentuk. Hanya-baca [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Mengembalikan atau mengatur tipe preset geometri. Catatan: saat nilai berubah, semua nilai penyesuaian akan direset ke nilai default mereka. Baca/tulis [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari bentuk. Hanya-baca [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti 3D. Hanya-baca [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain. Karena nilai ini dapat dialokasikan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi bentuk dalam urutan z. Shapes[0] mengembalikan bentuk paling belakang dalam urutan z, dan Shapes[Shapes.Count - 1] mengembalikan bentuk paling depan dalam urutan z. Hanya-baca Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Membuat dan mengembalikan array elemen bentuk. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini). Mengembalikan null jika bentuk saat ini tidak diwarisi. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Mengembalikan salinan jalur bentuk geometri. Koordinat relatif terhadap sudut kiri atas bentuk. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan gambar mini bentuk. Tipe batas gambar mini ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan gambar mini bentuk. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual bentuk yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Memperbarui geometri bentuk dari objek [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah tipe bentuk ([`ShapeType`](./shapetype)) menjadi Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Memperbarui geometri bentuk dari array [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah tipe bentuk ([`ShapeType`](./shapetype)) menjadi Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Bentuk sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Bentuk sebagai file SVG. |

### Lihat Juga

* kelas [Shape](../shape)
* antarmuka [IGeometryShape](../igeometryshape)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->