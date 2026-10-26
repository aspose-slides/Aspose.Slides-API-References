---
title: IConnector
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sebuah konektor.
type: docs
weight: 1847
url: /id/aspose.slides/iconnector/
---
## Kelas IConnector


Mewakili sebuah konektor.

```cpp
class IConnector : public virtual Aspose::Slides::IGeometryShape
```

## Metode

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Membuat dan mengembalikan array elemen shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Mengembalikan nilai penyesuaian shape pada indeks yang ditentukan. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Mengembalikan koleksi nilai penyesuaian shape. Hanya-baca [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Mengembalikan teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Mengembalikan judul teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Mengembalikan jumlah situs koneksi pada shape. Hanya-baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() | Mengembalikan kunci [Connector](../connector/). Hanya-baca [IConnectorLock](../iconnectorlock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Mengembalikan data khusus shape. Hanya-baca [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek piksel yang diterapkan pada shape. Hanya-baca [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() | Mengembalikan shape yang akan dihubungkan pada ujung konektor. Baca [IShape](../ishape/). |
| virtual **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() | Mengembalikan indeks situs koneksi untuk shape akhir. Baca **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti format isi untuk shape. Hanya-baca [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Mengembalikan properti frame shape. Baca [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Mengambil tinggi shape, diukur dalam poin. Baca **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Menentukan apakah shape tersembunyi. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Manajer hyperlink Hanya-baca [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Mengembalikan hyperlink yang didefinisikan untuk mouse over. Baca [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Mengambil opsi 'Tandai sebagai dekoratif' Baca/tulis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Menentukan apakah shape dikelompokkan. Hanya-baca **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Menentukan apakah shape adalah TextHolder. Hanya-baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti format garis untuk shape. Hanya-baca [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Mengembalikan nama shape. Baca [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama umur shape dan memungkinkan PowerPoint atau kode interop merujuk shape dengan andal dari mana saja dalam dokumen. Hanya-baca **uint32_t**. Lihat juga [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Mengembalikan objek induk [GroupShape](../groupshape/) jika shape dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Mengembalikan placeholder untuk shape. Hanya-baca [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Hanya-baca [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Mengembalikan properti mentah frame shape. Baca [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Mengembalikan jumlah derajat shape yang diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Mengembalikan kunci shape. Hanya-baca [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Mengembalikan objek gaya shape. Hanya-baca [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Mengembalikan tipe preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default mereka. Baca [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() | Mengembalikan shape yang akan dihubungkan pada awal konektor. Baca [IShape](../ishape/). |
| virtual **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() | Mengembalikan indeks situs koneksi untuk shape awal. Baca **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti format garis untuk shape. Hanya-baca [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lainnya. Karena nilai ini dapat diubah ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca **uint32_t**. Lihat juga [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Mengambil lebar shape, diukur dalam poin. Baca **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Mengambil koordinat x sudut kiri atas shape, diukur dalam poin. Baca **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Mengambil koordinat y sudut kiri atas shape, diukur dalam poin. Baca **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape paling belakang dalam urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape paling depan dalam urutan z. Hanya-baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Mengembalikan placeholder shape dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mengambil struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Mengembalikan salinan path geometri shape. Koordinat relatif terhadap sudut kiri atas shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Mengembalikan thumbnail shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) tipe batas thumbnail shape digunakan secara default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Mengembalikan thumbnail shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengambil tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan C# lock() untuk penguncian. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe objek dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Menetapkan bahwa shape ini bukan placeholder. |
| virtual void [Reroute](./reroute/)() | Mengarahkan ulang konektor sehingga mengambil jalur terpendek yang mungkin antara shape yang dihubungkannya. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Menetapkan teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Menetapkan judul teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Menetapkan shape yang akan dihubungkan pada ujung konektor. Tulis [IShape](../ishape/). |
| virtual void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) | Menetapkan indeks situs koneksi untuk shape akhir. Tulis **uint32_t**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Menetapkan properti frame shape. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Menetapkan tinggi shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Menentukan apakah shape tersembunyi. Tulis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Menetapkan hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Menetapkan hyperlink yang didefinisikan untuk mouse over. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Menetapkan opsi 'Tandai sebagai dekoratif' Baca/tulis **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Menetapkan nama shape. Tulis [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Menetapkan properti mentah frame shape. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Menetapkan jumlah derajat shape yang diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Menetapkan tipe preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default mereka. Tulis [Slides::ShapeType](../shapetype/). |
| virtual void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Menetapkan shape yang akan dihubungkan pada awal konektor. Tulis [IShape](../ishape/). |
| virtual void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) | Menetapkan indeks situs koneksi untuk shape awal. Tulis **uint32_t**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Menetapkan lebar shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Menetapkan koordinat x sudut kiri atas shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Menetapkan koordinat y sudut kiri atas shape, diukur dalam poin. Tulis **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Memperbarui geometri shape dari objek [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Memperbarui geometri shape dari array [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mengambil nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [IGeometryShape](../igeometryshape/)
* Namespace [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)