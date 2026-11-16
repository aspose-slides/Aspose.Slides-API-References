---
title: ChartPortionFormat
second_title: Referensi API Aspose.Sildes untuk .NET
description: Kelas ini berisi properti pemformatan bagian bagan yang digunakan dalam bagan. Tidak seperti IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata semua properti kelas ini dapat ditulis.
type: docs
weight: 1440
url: /id/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat kelas

This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Mengembalikan atau mengatur Id dari bahasa alternatif. Baca/tulis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Mengizinkan untuk mendapatkan antarmuka IPresentationComponent dasar. Baca-saja [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak ditentukan dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak ditentukan dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **float.NaN** berarti nilai tidak ditentukan dan harus diwarisi dari Master. Baca/tulis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Mengembalikan atau mengatur tinggi font pada bagian. **float.NaN** berarti tinggi tidak ditentukan dan harus diwarisi dari Master. Baca/tulis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Mengembalikan atau mengatur tipe underline teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Mengembalikan atau mengatur ukuran font minimal, untuk mana kerning harus diaktifkan. **float.NaN** berarti nilai tidak ditentukan dan harus diwarisi dari Master. Baca/tulis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Mengembalikan atau mengatur Id dari bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Mengembalikan atau mengatur info font Latin. Null berarti font tidak ditentukan dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Mengembalikan properti LineFormat untuk outline teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Menentukan apakah teks tidak harus diperiksa. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Mengembalikan atau mengatur kenaikan spasi antar karakter. **float.NaN** berarti nilai tidak ditentukan dan harus diwarisi dari Master. Baca/tulis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks tidak dilakukan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Mengembalikan atau mengatur tipe strikethrough teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Mengembalikan atau mengatur info font simbolik. Null berarti font tidak ditentukan dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Mengembalikan atau mengatur tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Mengembalikan properti FillFormat garis underline. Tidak ada pewarisan yang diterapkan. Baca-saja [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Mengembalikan properti LineFormat yang digunakan untuk outline garis underline. Tidak ada pewarisan yang diterapkan. Baca-saja [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda perlu menggunakan metode [`GetEffective`](../../aspose.slides/portionformat/geteffective) yang mengembalikan sebuah instance [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Lihat Juga

* kelas [BasePortionFormat](../../aspose.slides/baseportionformat)
* antarmuka [IChartPortionFormat](../ichartportionformat)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->