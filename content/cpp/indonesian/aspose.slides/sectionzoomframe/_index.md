---
title: SectionZoomFrame
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili objek Section Zoom dalam sebuah slide.
type: docs
weight: 5045
url: /id/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame kelas

Mewakili sebuah [Section](../section/) Zoom object pada slide.

```cpp
class SectionZoomFrame : public Aspose::Slides::ZoomObject,
                         public virtual Aspose::Slides::ISectionZoomFrame
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Mengembalikan teks alternatif yang terkait dengan sebuah bentuk. Baca [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Mengembalikan judul teks alternatif yang terkait dengan sebuah bentuk. Baca [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Properti menentukan bagaimana sebuah bentuk akan ditampilkan dalam mode hitam-putih. Baca [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Mengembalikan jumlah situs koneksi pada bentuk. Baca-saja **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Mengembalikan data khusus bentuk. Baca-saja [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Mengembalikan objek [EffectFormat](../effectformat/) yang berisi efek piksel yang diterapkan pada sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti efek. Baca-saja [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Mengembalikan objek [FillFormat](../fillformat/) yang berisi properti pemformatan isi untuk sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti isi. Baca-saja [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Mengembalikan properti bingkai bentuk. Baca [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Mengembalikan kunci bentuk. Baca-saja [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Mendapatkan tinggi bentuk, diukur dalam poin. Baca **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Menentukan apakah bentuk disembunyikan. Baca **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Mengembalikan manajer hyperlink. Baca-saja [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Mengembalikan hyperlink yang didefinisikan untuk mouse over. Baca [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Mendapatkan tipe gambar dari objek zoom. Baca [ZoomImageType](../zoomimagetype/). Nilai default: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Mendapatkan opsi 'Mark as decorative'. Reed/write **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Menentukan apakah bentuk dikelompokkan. Baca-saja **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Menentukan apakah bentuk adalah TextHolder_PPT. Baca-saja **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Mengembalikan objek [LineFormat](../lineformat/) yang berisi properti pemformatan garis untuk sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti garis. Baca-saja [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Mengembalikan nama sebuah bentuk. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Baca [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop mereferensikan bentuk secara andal dari mana saja dalam dokumen. Baca-saja **uint32_t**. Lihat juga [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Mengembalikan objek [GroupShape](../groupshape/) induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan null jika bentuk tidak memiliki placeholder. Baca-saja [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Mengembalikan presentasi induk dari sebuah slide. Baca-saja [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Mengembalikan properti bingkai bentuk mentah. Baca [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Mendapatkan perilaku navigasi dalam slideshow. Baca **bool**. Nilai default: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Mengembalikan jumlah derajat bentuk yang ditentukan diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Mengembalikan kunci bentuk. Baca-saja [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Mendapatkan nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca **bool**. Nilai default: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Mengembalikan slide induk dari sebuah bentuk. Baca-saja [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() override | Mendapatkan objek bagian yang ditautkan oleh objek Zoom [Section](../section/). Baca [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Mengembalikan objek [ThreeDFormat](../threedformat/) yang berisi properti efek 3d untuk sebuah bentuk. Catatan: dapat mengembalikan null untuk tipe bentuk tertentu yang tidak memiliki properti 3d. Baca-saja [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Mendapatkan durasi transisi antara Zoom dan slide. Baca **float**. Nilai default: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain. Karena nilai ini dapat dipindahtugaskan oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja **uint32_t**. Lihat juga [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Mendapatkan lebar bentuk, diukur dalam poin. Baca **float**. |
| **float** [get_X](../shape/get_x/)() override | Mendapatkan koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca **float**. |
| **float** [get_Y](../shape/get_y/)() override | Mendapatkan koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Mendapatkan gambar untuk objek zoom. Baca [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Mengembalikan posisi sebuah bentuk dalam urutan z. Shapes[0] mengembalikan bentuk di belakang urutan z, dan Shapes[Shapes.Count - 1] mengembalikan bentuk di depan urutan z. Baca-saja **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang menjadi sumber bentuk saat ini). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Mengembalikan thumbnail bentuk. Tipe batas thumbnail bentuk [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) digunakan secara default. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Mengembalikan thumbnail bentuk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan objek tipe nilai dengan nullptr melalui referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Menetapkan teks alternatif yang terkait dengan sebuah bentuk. Tulis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Menetapkan judul teks alternatif yang terkait dengan sebuah bentuk. Tulis [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Properti menentukan bagaimana sebuah bentuk akan ditampilkan dalam mode hitam-putih. Tulis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Menetapkan properti bingkai bentuk. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Menetapkan tinggi bentuk, diukur dalam poin. Tulis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Menentukan apakah bentuk disembunyikan. Tulis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Menetapkan hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Menetapkan hyperlink yang didefinisikan untuk mouse over. Tulis [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Menetapkan tipe gambar untuk objek zoom. Tulis [ZoomImageType](../zoomimagetype/). Nilai default: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Menetapkan opsi 'Mark as decorative'. Reed/write **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Menetapkan nama bentuk. Tidak boleh null. Gunakan nilai string kosong jika diperlukan. Tulis [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Menetapkan properti bingkai bentuk mentah. Tulis [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Menetapkan perilaku navigasi dalam slideshow. Tulis **bool**. Nilai default: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Menetapkan jumlah derajat bentuk yang ditentukan diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Tulis **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Menetapkan nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Tulis **bool**. Nilai default: true |
| void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | Menetapkan objek bagian yang ditautkan oleh objek Zoom [Section](../section/). Tulis [ISection](../isection/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Menetapkan durasi transisi antara Zoom dan slide. Tulis **float**. Nilai default: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Menetapkan lebar bentuk, diukur dalam poin. Tulis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Menetapkan koordinat x sudut kiri atas bentuk, diukur dalam poin. Tulis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Menetapkan koordinat y sudut kiri atas bentuk, diukur dalam poin. Tulis **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Menetapkan gambar untuk objek zoom. Tulis [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan beralih pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Menyimpan konten [Shape](../shape/) sebagai file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [ZoomObject](../zoomobject/)
* Kelas [ISectionZoomFrame](../isectionzoomframe/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)