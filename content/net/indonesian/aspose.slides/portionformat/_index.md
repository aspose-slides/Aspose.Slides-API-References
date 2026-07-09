---
title: PortionFormat
second_title: Referensi API Aspose.Sildes untuk .NET
description: Kelas ini berisi properti pemformatan bagian teks. Tidak seperti IPortionFormatEffectiveData./iportionformateffectivedata semua properti pada kelas ini dapat ditulis.
type: docs
weight: 9490
url: /id/aspose.slides/portionformat/
---
## PortionFormat kelas

Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [`IPortionFormatEffectiveData`](../iportionformateffectivedata), semua properti pada kelas ini dapat ditulis.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktor

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Menginisialisasi sebuah instance baru dari kelas [`PortionFormat`](../portionformat). |

## Properti

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Mengembalikan atau mengatur Id dari bahasa alternatif. Baca/tulis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar IPresentationComponent. Hanya-baca [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Mengembalikan atau mengatur pengidentifikasi bookmark. Baca/tulis String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Mengembalikan atau mengatur tinggi font suatu bagian. **float.NaN** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Menentukan apakah font miring (italik). Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Mengembalikan atau mengatur tipe underline teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Manajer hyperlink. Hanya-baca [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over. Baca/tulis [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Menentukan apakah angka harus mengabaikan tata letak vertikal teks khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Mengembalikan atau mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Mengembalikan atau mengatur info font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Mengembalikan properti LineFormat untuk garis tepi teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Menentukan apakah smart tag harus dibersihkan. Tidak ada pewarisan yang diterapkan. Baca/tulis Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Mengembalikan atau mengatur kenaikan jarak antar karakter. **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini disetel ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika disetel ke true, pemeriksaan ejaan diizinkan. Nilai default adalah `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Mengembalikan atau mengatur tipe coretan pada teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Mengembalikan atau mengatur info font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Mengembalikan atau mengatur tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Mengembalikan properti FillFormat garis underline. Tidak ada pewarisan yang diterapkan. Hanya-baca [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Mengembalikan properti LineFormat yang digunakan untuk menggarisbawahi garis underline. Tidak ada pewarisan yang diterapkan. Hanya-baca [`ILineFormat`](../ilineformat). |

## Metode

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Mendapatkan data pemformatan bagian yang efektif dengan pewarisan yang diterapkan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga pada kebanyakan kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda perlu menggunakan metode [`GetEffective`](./geteffective) yang mengembalikan sebuah instance [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Contoh

Contoh berikut menunjukkan cara menetapkan font Latin ke bagian Paragraph dalam Presentasi PowerPoint.

```csharp
[C#]
//Membuat objek presentasi yang mewakili file presentasi
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides menggunakan pengenal khusus ini (mirip dengan yang digunakan di PowerPoint):
// +mn-lt - Font Latin Badan (Font Latin Minor)
// +mj-lt - Font Latin Judul (Font Latin Mayor)
// +mn-ea - Font Asia Timur Badan (Font Asia Timur Minor)
// +mj-ea - Font Asia Timur Badan (Font Asia Timur Minor)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Lihat Juga

* kelas [BasePortionFormat](../baseportionformat)
* antarmuka [IPortionFormat](../iportionformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->