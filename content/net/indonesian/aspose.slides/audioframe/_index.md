---
title: AudioFrame
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili klip audio pada slide.
type: docs
weight: 850
url: /id/aspose.slides/audioframe/
---
## AudioFrame kelas

Mewakili klip audio pada slide.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Mengembalikan koleksi nilai penyesuaian shape. Read-only [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Read/write String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Mengembalikan atau mengatur indeks trek terakhir. Read/write Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Mengembalikan atau mengatur waktu trek terakhir. Read/write Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Mengembalikan atau mengatur indeks trek awal. Read/write Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Mengembalikan atau mengatur waktu trek awal. Read/write Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Mendapatkan koleksi caption tertutup yang terkait dengan audio frame. Properti ini hanya-baca dan mengembalikan [`ICaptionsCollection`](../icaptionscollection) yang berisi semua trek caption. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Mengembalikan jumlah situs koneksi pada shape. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Mengembalikan data khusus shape. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Read-only [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Menentukan apakah suara disematkan ke presentasi. Read-only Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Mengembalikan atau mengatur objek audio yang disematkan. Read/write [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Menentukan durasi waktu untuk fade-in awal media dalam milidetik. Read/write Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. Read/write Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti isi. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Mengembalikan atau mengatur properti frame shape. Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Mendapatkan atau mengatur tinggi shape, diukur dalam poin. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Menentukan apakah shape disembunyikan. Read/write Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Menentukan apakah AudioFrame disembunyikan. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Mengembalikan manajer hyperlink. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Read/write [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Menentukan apakah PictureFrame adalah objek Cameo atau tidak. Read only Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Mendapatkan atau mengatur opsi 'Mark as decorative'. Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Menentukan apakah shape dikelompokkan. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Menentukan apakah shape adalah TextHolder_PPT. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Read-only [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Mengembalikan atau mengatur nama file audio yang ditautkan ke AudioFrame. Read/write String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Mengembalikan atau mengatur nama shape. Tidak boleh null. Gunakan string kosong jika diperlukan. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop secara andal mereferensikan shape dari mana saja dalam dokumen. Read-only UInt32. Lihat juga [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Read-only [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Mengembalikan objek PictureFillFormat untuk frame gambar. Read-only [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Mengembalikan kunci shape. Read-only [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Read-only [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Menentukan apakah audio diputar melintasi slide. Read/write Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Menentukan apakah audio diulang. Read/write Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Mengembalikan atau mengatur mode pemutaran audio. Read/write [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Mengembalikan presentasi induk dari slide. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Mengembalikan atau mengatur properti frame shape mentah. Read/write [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1,0 sesuai dengan 100%. Read/write Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1,0 sesuai dengan 100%. Read/write Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah selesai. Read/write Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Mengembalikan atau mengatur jumlah derajat shape yang diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Read/write Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Mengembalikan kunci shape. Read-only [`IPictureFrameLock`](../ipictureframelock). (2 properti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Mengembalikan objek gaya shape. Read-only [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame. Semua item yang diizinkan dalam set [`ShapeType`](../shapetype), kecuali semua jenis garis: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Mengembalikan slide induk dari shape. Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3D. Read-only [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Read/write Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Read/write Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Read-only UInt32. Lihat juga [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Mengembalikan atau mengatur volume audio. Read/write [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Mengembalikan atau mengatur volume audio dalam persentase. Read/write Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Mendapatkan atau mengatur lebar shape, diukur dalam poin. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Mendapatkan atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Mendapatkan atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di bagian belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan z. Read-only Int32. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Membuat dan mengembalikan array elemen shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini). Null dikembalikan jika shape saat ini tidak diwarisi. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Mengembalikan thumbnail shape. Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Mengembalikan thumbnail shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Mendapatkan batas visual shape yang dihitung dari konten yang dirender. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Memperbarui geometri shape dari objek [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Memperbarui geometri shape dari array [`IGeometryPath`](../igeometrypath). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([`ShapeType`](../geometryshape/shapetype)) menjadi Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Menyimpan konten Shape sebagai file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Menyimpan konten Shape sebagai file SVG. |

### Contoh

Contoh berikut menunjukkan cara mengubah Opsi Pemutaran Audio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Mendapatkan shape AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Mengatur mode Putar menjadi putar pada klik
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Mengatur volume menjadi Rendah
    audioFrame.Volume = AudioVolumeMode.Low;
    // Mengatur audio untuk diputar melintasi slide
    audioFrame.PlayAcrossSlides = true;
    // Menonaktifkan pengulangan untuk audio
    audioFrame.PlayLoopMode = false;
    // Menyembunyikan AudioFrame selama tampilan slide
    audioFrame.HideAtShowing = true;
    // Memutar ulang audio ke awal setelah diputar
    audioFrame.RewindAudio = true;
    // Menyimpan file PowerPoint ke disk
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* kelas [PictureFrame](../pictureframe)
* antarmuka [IAudioFrame](../iaudioframe)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->