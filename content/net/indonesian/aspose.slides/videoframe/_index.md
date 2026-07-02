---
title: VideoFrame
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sebuah klip video pada slide.
type: docs
weight: 11700
url: /id/aspose.slides/videoframe/
---
## VideoFrame kelas

Mewakili sebuah klip video pada slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Mengembalikan koleksi nilai penyesuaian shape. Hanya-baca [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Mendapatkan koleksi caption tertutup yang terkait dengan video frame. Properti ini hanya-baca dan mengembalikan [`ICaptionsCollection`](../icaptionscollection) yang berisi semua trek caption. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Hanya-baca Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data kustom shape. Hanya-baca [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti efek. Hanya-baca [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Mengembalikan atau mengatur objek video tersemat. Baca/tulis [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format pengisian untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti pengisian. Hanya-baca [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Menentukan apakah video ditampilkan dalam mode layar penuh. Baca/tulis Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mendapatkan atau mengatur tinggi shape, diukur dalam point. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Baca/tulis Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Menentukan apakah VideoFrame disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan pengelola hyperlink. Hanya-baca [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Menentukan apakah PictureFrame adalah objek Cameo atau tidak. Hanya-baca Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mendapatkan atau mengatur opsi 'Tandai sebagai dekoratif'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Hanya-baca Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Hanya-baca Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti garis. Hanya-baca [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Mengembalikan atau mengatur nama file video yang terhubung ke VideoFrame. Baca/tulis String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Tidak boleh null. Gunakan string kosong jika diperlukan. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari mana saja dalam dokumen. Hanya-baca UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Mengembalikan objek PictureFillFormat untuk picture frame. Hanya-baca [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Mengembalikan kunci shape. Hanya-baca [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Hanya-baca [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Menentukan apakah video diputar berulang. Baca/tulis Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Mengembalikan atau mengatur mode pemutaran video. Baca/tulis [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Hanya-baca [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari picture frame. Nilai 1.0 sesuai dengan 100%. Baca/tulis Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari picture frame. Nilai 1.0 sesuai dengan 100%. Baca/tulis Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Menentukan apakah video secara otomatis diputar kembali ke awal begitu film selesai diputar. Baca/tulis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat shape yang diputar di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Mengembalikan kunci shape. Hanya-baca [`IPictureFrameLock`](../ipictureframelock). (2 properti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Mengembalikan objek style shape. Hanya-baca [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame. Terdapat semua item yang diperbolehkan dari set [`ShapeType`](../shapetype), kecuali semua jenis garis: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari shape. Hanya-baca [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti 3d. Hanya-baca [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Potong akhir [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Potong awal [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Mengembalikan atau mengatur volume audio. Baca/tulis [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mendapatkan atau mengatur lebar shape, diukur dalam point. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mendapatkan atau mengatur koordinat x sudut kiri-atas shape, diukur dalam point. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mendapatkan atau mengatur koordinat y sudut kiri-atas shape, diukur dalam point. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Hanya-baca Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Membuat dan mengembalikan array elemen shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini). Mengembalikan null jika shape saat ini tidak diwarisi. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Mengembalikan salinan path dari shape geometris. Koordinat relatif terhadap sudut kiri atas shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mendapatkan batas visual shape yang dihitung dari kontennya yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Memperbarui geometri shape dari objek [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Memperbarui geometri shape dari array [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [PictureFrame](../pictureframe)
* antarmuka [IVideoFrame](../ivideoframe)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->