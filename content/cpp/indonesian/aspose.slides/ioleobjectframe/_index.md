---
title: IOleObjectFrame
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili objek OLE pada slide.
type: docs
weight: 3095
url: /id/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame kelas

Represents an OLE object on a slide.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## Metode

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Mengembalikan teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Mengembalikan judul teks alternatif yang terkait dengan shape. Baca [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Properti menentukan bagaimana shape akan merender dalam mode tampilan hitam-putih.. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Mengembalikan jumlah situs koneksi pada shape. Baca-saja **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Mengembalikan data kustom shape. Baca-saja [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek piksel yang diterapkan pada shape. Baca-saja [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | Mendapatkan informasi tentang data OLE yang disematkan. Baca saja [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | Mengembalikan nama file objek OLE yang disematkan |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | Mengembalikan jalur objek OLE yang disematkan |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti format isian untuk shape. Baca-saja [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Mengembalikan properti bingkai shape. Baca [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Mengembalikan kunci shape. Baca-saja [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Mendapatkan tinggi shape, diukur dalam poin. Baca **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Menentukan apakah shape tersembunyi. Baca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Manajer hyperlink Baca-saja [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Mengembalikan hyperlink yang didefinisikan untuk hover mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Mendapatkan opsi 'Mark as decorative' Baca/tulis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Menentukan apakah shape dikelompokkan. Baca-saja **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | Menentukan apakah objek terlihat sebagai ikon. Baca **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | Menentukan apakah objek terhubung ke file eksternal. Baca-saja **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Menentukan apakah shape adalah TextHolder. Baca-saja **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti format garis untuk shape. Baca-saja [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan. Baca-saja [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. Baca saja [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Mengembalikan nama shape. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | Mengembalikan nama objek. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | Mengembalikan ProgID objek. Baca saja [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Mengembalikan pengenal unik berskala slide yang tetap konstan selama umur shape dan memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari mana saja dalam dokumen. Baca-saja **uint32_t**. Lihat juga [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Mengembalikan objek [GroupShape](../groupshape/) induk jika shape dikelompokkan. Jika tidak mengembalikan null. Baca-saja [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Mengembalikan placeholder untuk shape. Baca-saja [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Mengembalikan presentasi. Baca-saja [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Mengembalikan properti bingkai shape mentah. Baca [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Mengembalikan jumlah derajat rotasi shape yang ditentukan sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Mengembalikan kunci shape. Baca-saja [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Mengembalikan slide dasar. Baca-saja [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | Mengembalikan objek properti isian gambar OleObject. Baca-saja [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | Mengembalikan judul untuk ikon OleObject. Baca [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti format garis untuk shape. Baca-saja [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara program, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja **uint32_t**. Lihat juga [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | Menentukan apakah objek tersemat yang ditautkan otomatis diperbarui ketika presentasi dibuka atau dicetak. Baca **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Mendapatkan lebar shape, diukur dalam poin. Baca **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Mendapatkan koordinat x sudut kiri-atas shape, diukur dalam poin. Baca **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Mendapatkan koordinat y sudut kiri-atas shape, diukur dalam poin. Baca **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z. Baca-saja **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Mengembalikan thumbnail shape. Tipe batas thumbnail shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) digunakan secara default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Mengembalikan thumbnail shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Mendefinisikan bahwa shape ini bukan placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Mengatur teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Mengatur judul teks alternatif yang terkait dengan shape. Tulis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Properti menentukan bagaimana shape akan merender dalam mode tampilan hitam-putih.. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Mengatur properti bingkai shape. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Mengatur tinggi shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Menentukan apakah shape tersembunyi. Tulis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk hover mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Mengatur opsi 'Mark as decorative' Baca/tulis **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | Menentukan apakah objek terlihat sebagai ikon. Tulis **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Tulis [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Mengatur nama shape. Tulis [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | Mengatur nama objek. Tulis [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | Mengembalikan ProgID objek. Baca saja [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Mengatur properti bingkai shape mentah. Tulis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | Mengatur judul untuk ikon OleObject. Tulis [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | Menentukan apakah objek tersemat yang ditautkan otomatis diperbarui ketika presentasi dibuka atau dicetak. Tulis **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Mengatur lebar shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Tulis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Tulis **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | Mengatur informasi tentang data OLE yang disematkan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IGraphicalObject](../igraphicalobject/)
* RuangNama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)