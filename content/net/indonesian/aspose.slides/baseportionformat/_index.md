---
title: BasePortionFormat
second_title: Aspose.Sildes untuk Referensi API .NET
description: Properti pemformatan bagian teks umum.
type: docs
weight: 970
url: /id/aspose.slides/baseportionformat/
---
## BasePortionFormat kelas

Properti pemformatan bagian teks umum.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Mengembalikan atau mengatur Id bahasa alternatif. Baca/tulis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan mendapatkan antarmuka dasar IPresentationComponent. Baca-saja [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Mengembalikan atau mengatur informasi font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Mengembalikan atau mengatur informasi font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100 % (subskrip) hingga 100 % (superskrip). **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Mengembalikan atau mengatur tinggi font bagian teks. **float.NaN** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Mengembalikan atau mengatur jenis garis bawah teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Mengembalikan atau mengatur ukuran font minimal, untuk mana kerning harus diaktifkan. **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Mengembalikan atau mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Mengembalikan atau mengatur informasi font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Mengembalikan properti LineFormat untuk outline teks. Tidak ada pewarisan yang diterapkan. Baca-saja [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Baca/tulis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Mengembalikan atau mengatur penambahan spasi antar karakter. **float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Mengembalikan atau mengatur jenis coret pada teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Mengembalikan atau mengatur informasi font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Mengembalikan atau mengatur jenis kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Mengembalikan properti FillFormat garis bawah. Tidak ada pewarisan yang diterapkan. Baca-saja [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Mengembalikan properti LineFormat yang digunakan untuk outline garis bawah. Tidak ada pewarisan yang diterapkan. Baca-saja [`ILineFormat`](../ilineformat). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IBasePortionFormat](../ibaseportionformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->