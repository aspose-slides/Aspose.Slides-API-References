---
title: IShape
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sebuah bentuk pada slide.
type: docs
weight: 6930
url: /id/aspose.slides/ishape/
---
## antarmuka IShape

Mewakili sebuah bentuk pada slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk. Baca/tulis String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar IHyperlinkContainer. Baca-saja [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar ISlideComponent. Baca-saja [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Mengembalikan jumlah titik koneksi pada bentuk. Baca-saja Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Mengembalikan data khusus bentuk. Baca-saja [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada bentuk. Baca-saja [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti format isian untuk bentuk. Baca-saja [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Mengembalikan atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Menentukan apakah bentuk disembunyikan. Baca/tulis Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Mengembalikan atau mengatur opsi “Tandai sebagai dekoratif”. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Menentukan apakah bentuk dikelompokkan. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Menentukan apakah bentuk adalah TextHolder. Baca-saja Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti format garis untuk bentuk. Baca-saja [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Mengembalikan atau mengatur nama bentuk. Baca/tulis String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik lingkup slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop merujuk bentuk dengan andal dari mana saja dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Mengembalikan placeholder untuk bentuk. Baca-saja [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat bentuk diputar mengelilingi sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Mengembalikan kunci bentuk. Baca-saja [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti format garis untuk bentuk. Baca-saja [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal lingkup presentasi yang ditujukan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat diubah oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Mengembalikan atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Mengembalikan atau mengatur koordinat x sudut kiri-atas bentuk, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Mengembalikan atau mengatur koordinat y sudut kiri-atas bentuk, diukur dalam poin. Baca/tulis Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Mengembalikan posisi bentuk dalam urutan z. Shapes[0] mengembalikan bentuk paling belakang, dan Shapes[Shapes.Count - 1] mengembalikan bentuk paling depan. Baca-saja Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika belum ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini). Mengembalikan null jika bentuk saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Mengembalikan thumbnail bentuk. Tipe ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail bentuk. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Menetapkan bahwa bentuk ini bukan placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### See Also

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->