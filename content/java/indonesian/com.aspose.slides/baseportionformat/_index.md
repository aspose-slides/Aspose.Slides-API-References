---
title: BasePortionFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Properti pemformatan bagian teks umum.
type: docs
url: /id/com.aspose.slides/baseportionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Properti pemformatan bagian teks umum.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Mengembalikan properti LineFormat untuk outline teks. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan properti FillFormat teks. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan properti EffectFormat teks. |
| [getHighlightColor()](#getHighlightColor--) | Mengembalikan warna yang digunakan untuk menyorot teks. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Mengembalikan properti LineFormat yang digunakan untuk menggarisbawahi garis bawah. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Mengembalikan properti FillFormat garis bawah. |
| [getFontBold()](#getFontBold--) | Menentukan apakah fontnya tebal. |
| [setFontBold(byte value)](#setFontBold-byte-) | Menentukan apakah fontnya tebal. |
| [getFontItalic()](#getFontItalic--) | Menentukan apakah fontnya miring. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Menentukan apakah fontnya miring. |
| [getKumimoji()](#getKumimoji--) | Menentukan apakah angka harus mengabaikan tata letak vertikal teks khusus bahasa timur. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Menentukan apakah angka harus mengabaikan tata letak vertikal teks khusus bahasa timur. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Menentukan apakah tinggi teks harus dinormalisasi. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Menentukan apakah tinggi teks harus dinormalisasi. |
| [getProofDisabled()](#getProofDisabled--) | Menentukan apakah teks tidak perlu diperiksa ejaan. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Menentukan apakah teks tidak perlu diperiksa ejaan. |
| [getFontUnderline()](#getFontUnderline--) | Mengembalikan atau mengatur tipe garis bawah teks. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Mengembalikan atau mengatur tipe garis bawah teks. |
| [getTextCapType()](#getTextCapType--) | Mengembalikan atau mengatur tipe kapitalisasi teks. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Mengembalikan atau mengatur tipe kapitalisasi teks. |
| [getStrikethroughType()](#getStrikethroughType--) | Mengembalikan atau mengatur tipe coretan pada teks. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Mengembalikan atau mengatur tipe coretan pada teks. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. |
| [getFontHeight()](#getFontHeight--) | Mengembalikan atau mengatur tinggi font bagian. |
| [setFontHeight(float value)](#setFontHeight-float-) | Mengembalikan atau mengatur tinggi font bagian. |
| [getLatinFont()](#getLatinFont--) | Mengembalikan atau mengatur info font Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur info font Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Mengembalikan atau mengatur info font Asia Timur. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur info font Asia Timur. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Mengembalikan atau mengatur info font skrip kompleks. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur info font skrip kompleks. |
| [getSymbolFont()](#getSymbolFont--) | Mengembalikan atau mengatur info font simbolik. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur info font simbolik. |
| [getEscapement()](#getEscapement--) | Mengembalikan atau mengatur teks superskrip atau subskrip. |
| [setEscapement(float value)](#setEscapement-float-) | Mengembalikan atau mengatur teks superskrip atau subskrip. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. |
| [getLanguageId()](#getLanguageId--) | Mengembalikan atau mengatur Id bahasa pemeriksaan. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Mengembalikan atau mengatur Id bahasa pemeriksaan. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Mengembalikan atau mengatur Id bahasa alternatif. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Mengembalikan atau mengatur Id bahasa alternatif. |
| [getSpacing()](#getSpacing--) | Mengembalikan atau mengatur kenaikan spasi antar karakter. |
| [setSpacing(float value)](#setSpacing-float-) | Mengembalikan atau mengatur kenaikan spasi antar karakter. |
| [getSpellCheck()](#getSpellCheck--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Mengembalikan properti LineFormat untuk outline teks. Tidak ada pewarisan yang diterapkan. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Baca-saja [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Mengembalikan properti LineFormat yang digunakan untuk menggarisbawahi garis bawah. Tidak ada pewarisan yang diterapkan. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Mengembalikan properti FillFormat garis bawah. Tidak ada pewarisan yang diterapkan. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Menentukan apakah fontnya tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Menentukan apakah fontnya tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Menentukan apakah fontnya miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Menentukan apakah fontnya miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Menentukan apakah angka harus mengabaikan tata letak vertikal teks khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Menentukan apakah angka harus mengabaikan tata letak vertikal teks khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Menentukan apakah teks tidak perlu diperiksa ejaan. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Menentukan apakah teks tidak perlu diperiksa ejaan. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Mengembalikan atau mengatur tipe garis bawah teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Mengembalikan:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Mengembalikan atau mengatur tipe garis bawah teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Mengembalikan atau mengatur tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextCapType](../../com.aspose.slides/textcaptype).

**Mengembalikan:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Mengembalikan atau mengatur tipe kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextCapType](../../com.aspose.slides/textcaptype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Mengembalikan atau mengatur tipe coretan pada teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Mengembalikan:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Mengembalikan atau mengatur tipe coretan pada teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Menentukan apakah gaya garis bawah memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Menentukan apakah gaya garis bawah memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Mengembalikan atau mengatur tinggi font bagian. **Float.NaN** berarti tinggi tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Mengembalikan:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Mengembalikan atau mengatur tinggi font bagian. **Float.NaN** berarti tinggi tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Mengembalikan atau mengatur info font Latin. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Mengembalikan atau mengatur info font Latin. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Mengembalikan atau mengatur info font simbolik. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Mengembalikan atau mengatur info font simbolik. Null berarti font tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **Float.NaN** berarti nilai tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Mengembalikan:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **Float.NaN** berarti nilai tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. **Float.NaN** berarti nilai tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Mengembalikan:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. **Float.NaN** berarti nilai tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Mengembalikan atau mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Mengembalikan atau mengatur Id bahasa pemeriksaan. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Mengembalikan atau mengatur Id bahasa alternatif. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Mengembalikan atau mengatur Id bahasa alternatif. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Mengembalikan atau mengatur kenaikan spasi antar karakter. **Float.NaN** berarti nilai tidak didefinisikan dan harus diwariskan dari Master. Baca/tulis float .

**Mengembalikan:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Mengembalikan atau mengatur kenaikan spasi antar karakter. **Float.NaN** berarti nilai tidak didefinisikan dan harus diwarihkan dari Master. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah false .

**Mengembalikan:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini diatur ke false, pemeriksaan ejaan untuk elemen teks ditekan. Ketika diatur ke true, pemeriksaan ejaan diizinkan. Nilai default adalah false .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Akses potongan teks pertama di dalam bentuk pertama pada slide pertama
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktifkan pemeriksaan ejaan untuk potongan teks ini
>      portion.getPortionFormat().setSpellCheck(true);
>      // Simpan presentasi yang telah dimodifikasi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Akses potongan teks pertama di dalam bentuk pertama pada slide pertama
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktifkan pemeriksaan ejaan untuk potongan teks ini
>      portion.getPortionFormat().setSpellCheck(true);
>      // Simpan presentasi yang telah dimodifikasi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |