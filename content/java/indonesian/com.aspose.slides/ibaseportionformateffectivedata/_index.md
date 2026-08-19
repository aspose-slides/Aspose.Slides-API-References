---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Antarmuka dasar untuk objek tidak dapat diubah yang berisi properti pemformatan bagian teks yang efektif.
type: docs
url: /id/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Antarmuka dasar untuk objek tidak dapat diubah yang berisi properti pemformatan bagian teks yang efektif.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Mengembalikan properti LineFormat untuk penebaran teks. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan properti FillFormat teks. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan properti EffectFormat teks. |
| [getHighlightColor()](#getHighlightColor--) | Mengembalikan warna yang digunakan untuk menyorot teks. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Mengembalikan properti LineFormat yang digunakan untuk menggambar garis bawah. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Mengembalikan properti FillFormat garis bawah. |
| [getFontBold()](#getFontBold--) | Menentukan apakah font tebal. |
| [getFontItalic()](#getFontItalic--) | Menentukan apakah font miring. |
| [getKumimoji()](#getKumimoji--) | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Menentukan apakah tinggi teks harus dinormalisasi. |
| [getProofDisabled()](#getProofDisabled--) | Menentukan apakah teks tidak harus diperiksa ejaan. |
| [getFontUnderline()](#getFontUnderline--) | Mengembalikan tipe garis bawah teks. |
| [getTextCapType()](#getTextCapType--) | Mengembalikan tipe kapitalisasi teks. |
| [getStrikethroughType()](#getStrikethroughType--) | Mengembalikan tipe coret teks. |
| [getSmartTagClean()](#getSmartTagClean--) | Menentukan apakah smart tag harus dibersihkan. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. |
| [getFontHeight()](#getFontHeight--) | Mengembalikan tinggi font bagian teks, dalam poin. |
| [getLatinFont()](#getLatinFont--) | Mengembalikan info font Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Mengembalikan info font Asia Timur. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Mengembalikan info font skrip kompleks. |
| [getSymbolFont()](#getSymbolFont--) | Mengembalikan info font simbolik. |
| [getEscapement()](#getEscapement--) | Mengembalikan teks superskrip atau subskrip. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Mengembalikan ukuran font minimal, untuk mana kerning harus diaktifkan. |
| [getLanguageId()](#getLanguageId--) | Mengembalikan Id bahasa. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Mengembalikan Id bahasa alternatif. |
| [getSpacing()](#getSpacing--) | Mengembalikan penambahan jarak antar karakter, dalam poin. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Mengembalikan properti LineFormat untuk penebaran teks. Hanya-baca [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Mengembalikan:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Mengembalikan properti FillFormat teks. Hanya-baca [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Mengembalikan:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Mengembalikan properti EffectFormat teks. Hanya-baca [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Mengembalikan:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Mengembalikan warna yang digunakan untuk menyorot teks. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Mengembalikan properti LineFormat yang digunakan untuk menggambar garis bawah. Hanya-baca [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Mengembalikan:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Mengembalikan properti FillFormat garis bawah. Hanya-baca [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Mengembalikan:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Menentukan apakah font tebal. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Menentukan apakah font miring. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Menentukan apakah tinggi teks harus dinormalisasi. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Menentukan apakah teks tidak harus diperiksa ejaan. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Mengembalikan tipe garis bawah teks. Hanya-baca [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Mengembalikan:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Mengembalikan tipe kapitalisasi teks. Hanya-baca [TextCapType](../../com.aspose.slides/textcaptype).

**Mengembalikan:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Mengembalikan tipe coret teks. Hanya-baca [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Mengembalikan:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Menentukan apakah smart tag harus dibersihkan. Hanya-baca boolean.

**Mengembalikan:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Hanya-baca boolean.

**Mengembalikan:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Mengembalikan tinggi font bagian teks, dalam poin. Hanya-baca float.

**Mengembalikan:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Mengembalikan info font Latin. Hanya-baca [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Mengembalikan info font Asia Timur. Hanya-baca [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Mengembalikan info font skrip kompleks. Hanya-baca [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Mengembalikan info font simbolik. Hanya-baca [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Mengembalikan teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). Hanya-baca float.

**Mengembalikan:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Mengembalikan ukuran font minimal, untuk mana kerning harus diaktifkan. Hanya-baca float.

**Mengembalikan:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Mengembalikan Id bahasa. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Mengembalikan Id bahasa alternatif. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Mengembalikan penambahan jarak antar karakter, dalam poin. Hanya-baca float.

**Mengembalikan:**
float