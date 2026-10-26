---
title: IPortionFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas ini berisi properti pemformatan bagian teks. Tidak seperti IPortionFormatEffectiveData, semua properti kelas ini dapat ditulis.
type: docs
weight: 3329
url: /id/aspose.slides/iportionformat/
---
## IPortionFormat kelas


Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [IPortionFormatEffectiveData](../iportionformateffectivedata/), semua properti kelas ini dapat ditulis.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Mengembalikan Id bahasa alternatif. Baca [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Mengembalikan pengidentifikasi penanda buku. Baca [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Mengembalikan info font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Mengembalikan info font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Mengembalikan properti teks [EffectFormat](../effectformat/). Tidak ada pewarisan yang diterapkan. Baca-saja [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Mengembalikan teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Mengembalikan properti teks [FillFormat](../fillformat/). Tidak ada pewarisan yang diterapkan. Baca-saja [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Mengembalikan tinggi font suatu bagian. **std::numeric_limits<float>::quiet_NaN()** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Baca **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Mengembalikan jenis garis bawah teks. Tidak ada pewarisan yang diterapkan. Baca [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Baca-saja [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Mengembalikan hyperlink yang didefinisikan untuk klik mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Manajer hyperlink Baca-saja [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Mengembalikan hyperlink yang didefinisikan untuk hover mouse. Baca [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Menentukan apakah gaya garis bawah memiliki properti [FillFormat](../fillformat/) sendiri atau mewarisinya dari properti [FillFormat](../fillformat/) teks. Baca [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Menentukan apakah gaya garis bawah memiliki properti [LineFormat](../lineformat/) sendiri atau mewarisinya dari properti [LineFormat](../lineformat/) teks. Baca [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Mengembalikan ukuran font minimal, di mana kerning harus diaktifkan. **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Mengembalikan Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Mengembalikan info font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Mengembalikan properti [LineFormat](../lineformat/) untuk outline teks. Tidak ada pewarisan yang diterapkan. Baca-saja [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Baca [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Menentukan apakah smart tag harus dibersihkan. Tidak ada pewarisan yang diterapkan. Baca **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Mengembalikan kenaikan spasi antar karakter. **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Mendapatkan nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Mengembalikan jenis coret teks. Tidak ada pewarisan yang diterapkan. Baca [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Mengembalikan info font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Mengembalikan tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Mengembalikan properti garis bawah [FillFormat](../fillformat/). Tidak ada pewarisan yang diterapkan. Baca-saja [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Mengembalikan properti [LineFormat](../lineformat/) yang digunakan untuk outline garis bawah. Tidak ada pewarisan yang diterapkan. Baca-saja [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Mendapatkan data pemformatan bagian efektif dengan pewarisan yang diterapkan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan cloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama dengan nilai yang ditentukan. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Mengatur Id bahasa alternatif. Tulis [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Mengatur pengidentifikasi penanda buku. Tulis [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Mengatur info font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Tulis [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Mengatur info font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Tulis [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Tulis **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Mengatur tinggi font suatu bagian. **std::numeric_limits<float>::quiet_NaN()** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Tulis **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Mengatur jenis garis bawah teks. Tidak ada pewarisan yang diterapkan. Tulis [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk klik mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Mengatur hyperlink yang didefinisikan untuk hover mouse. Tulis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Menentukan apakah gaya garis bawah memiliki properti [FillFormat](../fillformat/) sendiri atau mewarisinya dari properti [FillFormat](../fillformat/) teks. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Menentukan apakah gaya garis bawah memiliki properti [LineFormat](../lineformat/) sendiri atau mewarisinya dari properti [LineFormat](../lineformat/) teks. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Mengatur ukuran font minimal, di mana kerning harus diaktifkan. **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Tulis **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Tulis [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Mengatur info font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Tulis [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Tulis [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Menentukan apakah smart tag harus dibersihkan. Tidak ada pewarisan yang diterapkan. Tulis **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Mengatur kenaikan spasi antar karakter. **std::numeric_limits<float>::quiet_NaN()** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Tulis **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Mengatur jenis coret teks. Tidak ada pewarisan yang diterapkan. Tulis [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Mengatur info font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Tulis [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Mengatur tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Tulis [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai penghitung referensi bersama saat ini. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan


Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan efektif termasuk yang diwarisi, Anda perlu menggunakan metode [IPortionFormat::GetEffective](./geteffective/) yang mengembalikan sebuah instance [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Lihat Juga

* Kelas [IBasePortionFormat](../ibaseportionformat/)
* Kelas [IHyperlinkContainer](../ihyperlinkcontainer/)
* RuangNama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)