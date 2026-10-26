---
title: IAudioFrame
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili klip audio pada slide.
type: docs
weight: 1353
url: /id/aspose.slides/iaudioframe/
---
## IAudioFrame kelas

Mewakili klip audio pada slide.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Metode

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Membuat dan mengembalikan array elemen shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mengemulasi perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Mengembalikan nilai penyesuaian shape pada indeks yang ditentukan. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Mengembalikan koleksi nilai penyesuaian shape. Hanya baca [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Mengembalikan teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Mengembalikan judul teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Mengembalikan indeks trek terakhir Baca **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Mengembalikan waktu trek terakhir. Baca **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Mengembalikan indeks trek awal. Baca **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Mengembalikan waktu trek awal. Baca **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Mendapatkan koleksi caption tertutup yang terkait dengan audio frame. Properti ini hanya baca dan mengembalikan sebuah [ICaptionsCollection](../icaptionscollection/) yang berisi semua trek caption. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Mengembalikan jumlah situs koneksi pada shape. Hanya baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Mengembalikan data khusus shape. Hanya baca [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek pixel yang diterapkan pada shape. Hanya baca [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Menentukan apakah suara disematkan ke presentasi. Hanya baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Mengembalikan objek audio yang disematkan. Baca [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Menentukan durasi waktu fade-in awal media dalam milidetik. Baca **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Menentukan durasi waktu fade-out akhir media dalam milidetik. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti format pengisian untuk shape. Hanya baca [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Mengembalikan properti frame shape. Baca [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Mendapatkan tinggi shape, diukur dalam point. Baca **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Menentukan apakah shape tersembunyi. Baca **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Menentukan apakah [AudioFrame](../audioframe/) tersembunyi. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Manajer hyperlink Hanya baca [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Mengembalikan hyperlink yang didefinisikan untuk mouse over. Baca [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Mendapatkan opsi 'Mark as decorative'. Baca/tulis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Menentukan apakah shape dikelompokkan. Hanya baca **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Menentukan apakah shape adalah TextHolder. Hanya baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti format garis untuk shape. Hanya baca [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Mengembalikan nama file audio yang ditautkan ke [AudioFrame](../audioframe/). Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Mengembalikan nama shape. Baca [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama umur shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari mana saja dalam dokumen. Hanya baca **uint32_t**. Lihat juga [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Mengembalikan objek parent [GroupShape](../groupshape/) jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya baca [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Mengembalikan objek [PictureFillFormat](../picturefillformat/) untuk frame gambar. Hanya baca [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Mengembalikan kunci [PictureFrame](../pictureframe/). Hanya baca [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Mengembalikan placeholder untuk shape. Hanya baca [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Menentukan apakah audio diputar melintasi slide. Baca **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Menentukan apakah audio diulang. Baca **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Mengembalikan mode pemutaran audio. Baca [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya baca [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Mengembalikan properti frame shape mentah. Baca [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Mengembalikan skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%. Baca **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Mengembalikan skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%. Baca **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Mengembalikan jumlah derajat rotasi shape yang ditentukan sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Mengembalikan kunci shape. Hanya baca [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Mengembalikan objek style shape. Hanya baca [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Mengembalikan tipe preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai defaultnya. Baca [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya baca [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti format garis untuk shape. Hanya baca [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Mengembalikan identifier internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat diubah kembali oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya baca **uint32_t**. Lihat juga [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Mengembalikan volume audio. Baca [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Mengembalikan volume audio dalam persen. Baca **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Mendapatkan lebar shape, diukur dalam point. Baca **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Mendapatkan koordinat x sudut kiri atas shape, diukur dalam point. Baca **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Mendapatkan koordinat y sudut kiri atas shape, diukur dalam point. Baca **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Hanya baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Mengembalikan thumbnail shape. Tipe batas thumbnail shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) digunakan secara default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Mengembalikan thumbnail shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan menyalin konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan menyalin konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi jumlah referensi berbagi dengan nilai yang ditentukan. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Mengatur teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Mengatur judul teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Mengatur indeks trek terakhir Tulis **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Mengatur waktu trek terakhir. Tulis **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Mengatur indeks trek awal. Tulis **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Mengatur waktu trek awal. Tulis **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Properti menentukan bagaimana shape akan ditampilkan dalam mode hitam-putih. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Mengatur objek audio yang disematkan. Tulis [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Menentukan durasi waktu fade-in awal media dalam milidetik. Tulis **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Menentukan durasi waktu fade-out akhir media dalam milidetik. Tulis **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Mengatur properti frame shape. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Mengatur tinggi shape, diukur dalam point. Tulis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Menentukan apakah shape tersembunyi. Tulis **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Menentukan apakah [AudioFrame](../audioframe/) tersembunyi. Tulis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk mouse over. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Mengatur opsi 'Mark as decorative'. Baca/tulis **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Mengatur nama file audio yang ditautkan ke [AudioFrame](../audioframe/). Tulis [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Mengatur nama shape. Tulis [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Menentukan apakah audio diputar melintasi slide. Tulis **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Menentukan apakah audio diulang. Tulis **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Mengatur mode pemutaran audio. Tulis [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Mengatur properti frame shape mentah. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%. Tulis **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Mengatur skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%. Tulis **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Tulis **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Mengatur tipe preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai defaultnya. Tulis [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Tulis **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Tulis **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Mengatur volume audio. Tulis [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Mengatur volume audio dalam persen. Tulis **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Mengatur lebar shape, diukur dalam point. Tulis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Mengatur koordinat x sudut kiri atas shape, diukur dalam point. Tulis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Mengatur koordinat y sudut kiri atas shape, diukur dalam point. Tulis **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Memperbarui geometri shape dari objek [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Memperbarui geometri shape dari array [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai terkini penghitung referensi berbagi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi berbagi. Tidak seharusnya dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi berbagi. Tidak seharusnya dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [IPictureFrame](../ipictureframe/)
* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)