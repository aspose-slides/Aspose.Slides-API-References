---
title: SmartArt
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili diagram SmartArt
type: docs
weight: 10580
url: /id/aspose.slides.smartart/smartart/
---
## Kelas SmartArt

Mewakili diagram SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Mengembalikan koleksi semua node dalam objek SmartArt. Hanya-baca [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape. Baca/tulis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana sebuah shape akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Mengembalikan atau mengatur gaya warna dari objek SmartArt. Baca/tulis [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah titik koneksi pada shape. Hanya-baca Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus shape. Hanya-baca [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Hanya-baca [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format pengisian untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti pengisian. Hanya-baca [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai shape. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci shape. Hanya-baca [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi shape, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Hanya-baca [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Mark as decorative'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Hanya-baca Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Mengembalikan atau mengatur status diagram SmartArt terkait (left-to-right) LTR atau (right-to-left) RTL, jika diagram mendukung pembalikan. Baca/tulis Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Hanya-baca Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Mengembalikan atau mengatur tata letak objek SmartArt. Baca/tulis [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Hanya-baca [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca/tulis String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Mengembalikan koleksi node akar dalam objek SmartArt. Hanya-baca [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape dengan dapat diandalkan dari mana saja dalam dokumen. Hanya-baca UInt32. Lihat juga [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk sebuah shape. Mengembalikan null jika shape tidak memiliki placeholder. Hanya-baca [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari sebuah slide. Hanya-baca [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Mengembalikan atau mengatur gaya cepat objek SmartArt. Baca/tulis [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai shape mentah. Baca/tulis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat rotasi shape tertentu sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci shape. Hanya-baca [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari sebuah shape. Hanya-baca [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3d. Hanya-baca [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang ditujukan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca UInt32. Lihat juga [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar shape, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Hanya-baca Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual shape yang dihitung dari kontennya yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Lihat Juga

* kelas [GraphicalObject](../../aspose.slides/graphicalobject)
* antarmuka [ISmartArt](../ismartart)
* ruang nama [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->