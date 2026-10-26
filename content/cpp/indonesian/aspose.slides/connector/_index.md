---
title: Connector
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sebuah konektor.
type: docs
weight: 482
url: /id/aspose.slides/connector/
---
## Kelas Connector

Mewakili sebuah konektor.

```cpp
class Connector : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IConnector
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Membuat dan mengembalikan array elemen shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Mengembalikan nilai penyesuaian shape pada indeks yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Mengembalikan koleksi nilai penyesuaian shape. Baca-saja [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Mengembalikan teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Mengembalikan judul teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Properti menentukan bagaimana shape akan ditampilkan dalam mode hitam-putih. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Mengembalikan jumlah titik koneksi pada shape. Baca-saja **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() override | Mengembalikan kunci konektor. Baca-saja [IConnectorLock](../iconnectorlock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Mengembalikan data khusus shape. Baca-saja [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek piksel yang diterapkan pada shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti efek. Baca-saja [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() override | Mengembalikan shape yang akan dihubungkan pada ujung konektor. Baca [IShape](../ishape/). |
| **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() override | Mengembalikan indeks titik koneksi untuk shape akhir. Baca **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti pemformatan isi untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti isi. Baca-saja [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Mengembalikan properti bingkai shape. Baca [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Mendapatkan tinggi shape, diukur dalam poin. Baca **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Menentukan apakah shape tersembunyi. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Mengembalikan hyperlink yang ditentukan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Mengembalikan manajer hyperlink. Baca-saja [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Mengembalikan hyperlink yang ditentukan untuk hover mouse. Baca [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Mendapatkan opsi 'Mark as decorative' **bool** Baca/tulis. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Menentukan apakah shape dikelompokkan. Baca-saja **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Menentukan apakah shape adalah TextHolder_PPT. Baca-saja **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti pemformatan garis untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti garis. Baca-saja [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Mengembalikan nama shape. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape dengan handal dari mana saja dalam dokumen. Baca-saja **uint32_t**. Lihat juga [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Mengembalikan objek [GroupShape](../groupshape/) induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Mengembalikan placeholder untuk shape. Mengembalikan null jika shape tidak memiliki placeholder. Baca-saja [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Mengembalikan presentasi induk dari slide. Baca-saja [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Mengembalikan properti bingkai shape mentah. Baca [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Mengembalikan jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Mengembalikan kunci shape. Baca-saja [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Mengembalikan objek gaya shape. Baca-saja [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | Mengembalikan tipe [AutoShape](../autoshape/). Baca [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Mengembalikan slide induk dari shape. Baca-saja [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() override | Mengembalikan shape yang akan dihubungkan pada awal konektor. Baca [IShape](../ishape/). |
| **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() override | Mengembalikan indeks titik koneksi untuk shape awal. Baca **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti efek 3D untuk shape. Catatan: dapat mengembalikan null untuk tipe shape tertentu yang tidak memiliki properti 3D. Baca-saja [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lainnya. Karena nilai ini dapat dipindahtugaskan oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja **uint32_t**. Lihat juga [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Mendapatkan lebar shape, diukur dalam poin. Baca **float**. |
| **float** [get_X](../shape/get_x/)() override | Mendapatkan koordinat x sudut kiri atas shape, diukur dalam poin. Baca **float**. |
| **float** [get_Y](../shape/get_y/)() override | Mendapatkan koordinat y sudut kiri atas shape, diukur dalam poin. Baca **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Mengembalikan posisi shape dalam urutan-z. Shapes[0] mengembalikan shape di belakang urutan-z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan-z. Baca-saja **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Mengembalikan thumbnail shape. Tipe batas thumbnail shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) digunakan secara default. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Mengembalikan thumbnail shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Mendapatkan batas visual shape yang dihitung dari konten yang dirender. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instansi tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak benar-benarnya menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak benar-benarnya menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Mendefinisikan bahwa shape ini bukan placeholder. |
| void [Reroute](./reroute/)() override | Mengarahkan ulang konektor sehingga mengambil jalur terpendek antara shape yang dihubungkannya. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Menetapkan teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Menetapkan judul teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Properti menentukan bagaimana shape akan ditampilkan dalam mode hitam-putih. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Menetapkan shape yang akan dihubungkan pada ujung konektor. Tulis [IShape](../ishape/). |
| void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) override | Menetapkan indeks titik koneksi untuk shape akhir. Tulis **uint32_t**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Menetapkan properti bingkai shape. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Menetapkan tinggi shape, diukur dalam poin. Tulis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Menentukan apakah shape tersembunyi. Tulis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Menetapkan hyperlink yang ditentukan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Menetapkan hyperlink yang ditentukan untuk hover mouse. Tulis [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Menetapkan opsi 'Mark as decorative' **bool** Baca/tulis. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Menetapkan nama shape. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Tulis [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Menetapkan properti bingkai shape mentah. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Menetapkan jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Menetapkan tipe [AutoShape](../autoshape/). Tulis [Slides::ShapeType](../shapetype/). |
| void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Menetapkan shape yang akan dihubungkan pada awal konektor. Tulis [IShape](../ishape/). |
| void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) override | Menetapkan indeks titik koneksi untuk shape awal. Tulis **uint32_t**. |
| void [set_Width](../shape/set_width/)(**float**) override | Menetapkan lebar shape, diukur dalam poin. Tulis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Menetapkan koordinat x sudut kiri atas shape, diukur dalam poin. Tulis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Menetapkan koordinat y sudut kiri atas shape, diukur dalam poin. Tulis **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Memperbarui geometri shape dari objek [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Memperbarui geometri shape dari array [IGeometryPath](../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../shapetype/)) menjadi [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [GeometryShape](../geometryshape/)
* Kelas [IConnector](../iconnector/)
* Namespace [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)