---
title: AudioFrame
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili klip audio pada slide.
type: docs
weight: 53
url: /id/aspose.slides/audioframe/
---
## AudioFrame kelas

Mewakili klip audio pada slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Membuat dan mengembalikan array elemen shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Mengembalikan nilai penyesuaian shape pada indeks yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Mengembalikan koleksi nilai penyesuaian shape. Hanya-baca [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Mengembalikan teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Mengembalikan judul teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Mengembalikan indeks trek terakhir Baca **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Mengembalikan waktu trek terakhir. Baca **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Mengembalikan indeks trek awal. Baca **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Mengembalikan waktu trek awal. Baca **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Mendapatkan koleksi caption tertutup yang terkait dengan audio frame. Properti ini hanya-baca dan mengembalikan sebuah [ICaptionsCollection](../icaptionscollection/) yang berisi semua trek caption. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Mengembalikan jumlah situs koneksi pada shape. Hanya-baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Mengembalikan data khusus shape. Hanya-baca [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek piksel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Hanya-baca [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Menentukan apakah suara disematkan ke presentasi. Hanya-baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Mengembalikan objek audio yang disematkan. Baca [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Menentukan durasi waktu fade-in awal media dalam milidetik. Baca **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Menentukan durasi waktu fade-out akhir media dalam milidetik. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti format isian untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti isian. Hanya-baca [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Mengembalikan properti frame shape. Baca [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Mendapatkan tinggi shape, diukur dalam poin. Baca **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Menentukan apakah shape tersembunyi. Baca **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Menentukan apakah [AudioFrame](./) tersembunyi. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Mengembalikan manajer hyperlink. Hanya-baca [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Mengembalikan hyperlink yang didefinisikan untuk hover mouse. Baca [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Menentukan apakah [PictureFrame](../pictureframe/) adalah objek Cameo atau tidak. Hanya-baca **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Mendeteksi opsi 'Mark as decorative' Baca/tulis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Menentukan apakah shape dikelompokkan. Hanya-baca **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Menentukan apakah shape adalah TextHolder_PPT. Hanya-baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti format garis untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Hanya-baca [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Mengembalikan nama file audio yang ditautkan ke [AudioFrame](./). Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Mengembalikan nama shape. Harus tidak null. Gunakan nilai string kosong jika diperlukan. Baca [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen. Hanya-baca **uint32_t**. Lihat juga [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Mengembalikan objek [GroupShape](../groupshape/) induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Mengembalikan objek [PictureFillFormat](../picturefillformat/) untuk frame gambar. Hanya-baca [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Mengembalikan kunci shape. Hanya-baca [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Hanya-baca [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Menentukan apakah audio diputar melintasi slide. Baca **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Menentukan apakah audio diulang. Baca **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Mengembalikan mode pemutaran audio. Baca [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Mengembalikan presentasi induk dari slide. Hanya-baca [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Mengembalikan properti frame shape mentah. Baca [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Mengembalikan skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 bersesuaian dengan 100%. Baca **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Mengembalikan skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 bersesuaian dengan 100%. Baca **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Mengembalikan jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Mengembalikan kunci shape. Hanya-baca [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Mengembalikan objek gaya shape. Hanya-baca [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Mengembalikan slide induk dari shape. Hanya-baca [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti efek 3d untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3d. Hanya-baca [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. Baca **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. Baca **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Mengembalikan pengenal internal berskala presentasi yang ditujukan untuk digunakan oleh add-in atau kode lainnya. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca **uint32_t**. Lihat juga [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Mengembalikan volume audio. Baca [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Mengembalikan volume audio dalam persen. Baca **float**. |
| **float** [get_Width](../shape/get_width/)() override | Mendapatkan lebar shape, diukur dalam poin. Baca **float**. |
| **float** [get_X](../shape/get_x/)() override | Mendapatkan koordinat x sudut kiri-atas shape, diukur dalam poin. Baca **float**. |
| **float** [get_Y](../shape/get_y/)() override | Mendapatkan koordinat y sudut kiri-atas shape, diukur dalam poin. Baca **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Hanya-baca **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Mengembalikan thumbnail shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) tipe batas thumbnail shape digunakan secara default. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Mengembalikan thumbnail shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Mendapatkan batas visual shape yang dihitung dari kontennya yang dirender. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Mendefinisikan bahwa shape ini bukan placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Mengatur teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Mengatur judul teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Mengatur indeks trek terakhir Tulis **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Mengatur waktu trek terakhir. Tulis **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Mengatur indeks trek awal. Tulis **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Mengatur waktu trek awal. Tulis **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Mengatur objek audio yang disematkan. Tulis [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Menentukan durasi waktu fade-in awal media dalam milidetik. Tulis **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Menentukan durasi waktu fade-out akhir media dalam milidetik. Tulis **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Mengatur properti frame shape. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Mengatur tinggi shape, diukur dalam poin. Tulis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Menentukan apakah shape tersembunyi. Tulis **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Menentukan apakah [AudioFrame](./) tersembunyi. Tulis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Mengatur hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Mengatur hyperlink yang didefinisikan untuk hover mouse. Tulis [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Mengatur opsi 'Mark as decorative' Baca/tulis **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Mengatur nama file audio yang ditautkan ke [AudioFrame](./). Tulis [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Mengatur nama shape. Harus tidak null. Gunakan nilai string kosong jika diperlukan. Tulis [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Menentukan apakah audio diputar melintasi slide. Tulis **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Menentukan apakah audio diulang. Tulis **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Mengatur mode pemutaran audio. Tulis [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Mengatur properti frame shape mentah. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 bersesuaian dengan 100%. Tulis **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Mengatur skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 bersesuaian dengan 100%. Tulis **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Tulis **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Mengatur jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Menentukan durasi waktu yang dihapus dari akhir media selama pemutaran, dalam milidetik. Tulis **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Menentukan durasi waktu yang dihapus dari awal media selama pemutaran, dalam milidetik. Tulis **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Mengatur volume audio. Tulis [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Mengatur volume audio dalam persen. Tulis **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Mengatur lebar shape, diukur dalam poin. Tulis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Tulis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Tulis **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Memperbarui geometri shape dari objek [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Memperbarui geometri shape dari array [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Catatan

Contoh berikut menunjukkan cara mengubah [Audio](../audio/) Play Options. 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Mendapatkan shape AudioFrame
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Mengatur mode pemutaran menjadi diputar pada klik
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Mengatur volume menjadi Rendah
audioFrame->set_Volume(AudioVolumeMode::Low);
// Mengatur audio untuk diputar melintasi slide
audioFrame->set_PlayAcrossSlides(true);
// Menonaktifkan pengulangan untuk audio
audioFrame->set_PlayLoopMode(false);
// Menyembunyikan AudioFrame selama pertunjukan slide
audioFrame->set_HideAtShowing(true);
// Memutar ulang audio ke awal setelah diputar
audioFrame->set_RewindAudio(true);
// Menyimpan file PowerPoint ke disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [PictureFrame](../pictureframe/)
* Kelas [IAudioFrame](../iaudioframe/)
* Ruang nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)