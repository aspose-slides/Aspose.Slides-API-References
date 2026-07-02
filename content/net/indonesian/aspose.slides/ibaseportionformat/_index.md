---
title: IBasePortionFormat
second_title: Aspose.Sildes untuk Referensi API .NET
description: Kelas ini berisi properti pemformatan bagian teks. Tidak seperti IPortionFormatEffectiveData./iportionformateffectivedata semua properti kelas ini dapat ditulis.
type: docs
weight: 5290
url: /id/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat antarmuka

Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [`IPortionFormatEffectiveData`](../iportionformateffectivedata), semua properti kelas ini dapat ditulis.

```csharp
public interface IBasePortionFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Mengembalikan atau mengatur Id dari bahasa alternatif. Read/write String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Mengembalikan atau mengatur informasi font skrip kompleks. Null berarti font tidak ditentukan dan harus diwariskan dari Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Mengembalikan atau mengatur informasi font Asia Timur. Null berarti font tidak ditentukan dan harus diwariskan dari Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100 % (subskrip) hingga 100 % (superskrip). **float.NaN** berarti nilai tidak ditentukan dan harus diwariskan dari Master. Read/write Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Menentukan apakah font ditebalkan. Tidak ada pewarisan yang diterapkan. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Mengembalikan atau mengatur tinggi font bagian. **float.NaN** berarti tinggi tidak ditentukan dan harus diwariskan dari Master. Read/write Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Menentukan apakah font miring (italic). Tidak ada pewarisan yang diterapkan. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Mengembalikan atau mengatur jenis garis bawah teks. Tidak ada pewarisan yang diterapkan. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Mengembalikan atau mengatur ukuran font minimal, untuk mana kerning harus diaktifkan. **float.NaN** berarti nilai tidak ditentukan dan harus diwariskan dari Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Mengembalikan atau mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Read/write String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Mengembalikan atau mengatur informasi font Latin. Null berarti font tidak ditentukan dan harus diwariskan dari Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Mengembalikan properti LineFormat untuk outline teks. Tidak ada pewarisan yang diterapkan. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Menentukan apakah teks tidak boleh diperiksa ejaannya. Tidak ada pewarisan yang diterapkan. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Mengembalikan atau mengatur kenaikan spasi antar karakter. **float.NaN** berarti nilai tidak ditentukan dan harus diwariskan dari Master. Read/write Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Mengembalikan atau mengatur jenis coret pada teks. Tidak ada pewarisan yang diterapkan. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Mengembalikan atau mengatur informasi font simbolik. Null berarti font tidak ditentukan dan harus diwariskan dari Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Mengembalikan atau mengatur jenis kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Mengembalikan properti FillFormat garis bawah. Tidak ada pewarisan yang diterapkan. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Mengembalikan properti LineFormat yang digunakan untuk memberi outline pada garis bawah. Tidak ada pewarisan yang diterapkan. Read-only [`ILineFormat`](../ilineformat). |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mendapatkan nilai sehingga dalam kebanyakan kasus Anda akan menerima nilai yang berarti "tidak terdefinisi".

Untuk memperoleh nilai parameter pemformatan yang efektif termasuk yang diwariskan, Anda perlu menggunakan metode [`GetEffective`](../iportionformat/geteffective) yang mengembalikan sebuah instance [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Lihat Juga

* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->