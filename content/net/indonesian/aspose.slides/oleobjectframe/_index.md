---
title: OleObjectFrame
second_title: Aspose.Sildes untuk .NET Referensi API
description: Mewakili objek OLE pada slide.
type: docs
weight: 9210
url: /id/aspose.slides/oleobjectframe/
---
## OleObjectFrame kelas

Mewakili objek OLE pada slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Memungkinkan mendapatkan antarmuka IGraphicalObject dasar. Baca-saja [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Baca/tulis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Baca-saja Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus shape. Baca-saja [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek pixel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Baca-saja [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Mengambil atau mengatur informasi tentang data OLE yang tertanam. Baca/tulis [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Mengembalikan nama file objek OLE yang tertanam |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Mengembalikan jalur objek OLE yang tertanam |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti isi. Baca-saja [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mengambil atau mengatur tinggi shape, diukur dalam poin. Baca/tulis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Baca/tulis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Baca-saja [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'. Baca/tulis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Baca-saja Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Menentukan apakah objek terlihat sebagai ikon. Baca/tulis Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Menentukan apakah objek terhubung ke file eksternal. Baca-saja Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Baca-saja Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Baca-saja [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan. Baca-saja String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca/tulis String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. Baca-saja String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Tidak boleh null. Gunakan nilai string kosong bila diperlukan. Baca/tulis String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Mengembalikan atau mengatur nama objek. Baca/tulis String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Mengembalikan ProgID objek. Baca-saja String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari manapun dalam dokumen. Baca-saja UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Baca-saja [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Baca-saja [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat shape yang ditentukan diputar mengelilingi sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Mengembalikan kunci shape. Baca-saja [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari shape. Baca-saja [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Mengembalikan objek properti isi gambar OleObject. Baca-saja [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3d. Baca-saja [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan kembali oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Menentukan apakah objek tertaut yang tertanam otomatis diperbarui ketika presentasi dibuka atau dicetak. Baca/tulis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mengambil atau mengatur lebar shape, diukur dalam poin. Baca/tulis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mengambil atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Baca/tulis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mengambil atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Baca/tulis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Baca-saja Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe ShapeThumbnailBounds.Shape digunakan secara default untuk batas thumbnail shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Mengatur informasi tentang data OLE yang tertanam. Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menandakan bahwa objek OLE tertanam. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Contoh

Contoh berikut menunjukkan cara mengakses frame OLE Object.

```csharp
[C#]
// Memuat PPTX ke objek presentasi
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Mengakses slide pertama
    ISlide sld = pres.Slides[0];
    // Mencast shape ke OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Membaca OLE Object dan menulisnya ke disk
    if (oleObjectFrame != null)
    {
        // Mengambil data file yang tertanam
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Mengambil ekstensi file yang tertanam
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Membuat jalur untuk menyimpan file yang diekstrak
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Menyimpan data yang diekstrak
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Lihat Juga

* kelas [GraphicalObject](../graphicalobject)
* antarmuka [IOleObjectFrame](../ioleobjectframe)
* ruangnama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->