---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Kelas ini berisi properti pemformatan bagian teks.
type: docs
url: /id/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), semua properti kelas ini dapat ditulis.

--------------------

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga untuk sebagian besar kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter format efektif termasuk yang diwarisi, Anda harus menggunakan metode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) yang mengembalikan instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Mengembalikan properti LineFormat untuk outline teks. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan properti FillFormat teks. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan properti EffectFormat teks. |
| [getHighlightColor()](#getHighlightColor--) | Mengembalikan warna yang digunakan untuk menyorot teks. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Mengembalikan properti LineFormat yang digunakan untuk menyorot garis bawah. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Mengembalikan properti FillFormat garis bawah. |
| [getFontBold()](#getFontBold--) | Menentukan apakah font tebal. |
| [setFontBold(byte value)](#setFontBold-byte-) | Menentukan apakah font tebal. |
| [getFontItalic()](#getFontItalic--) | Menentukan apakah font miring. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Menentukan apakah font miring. |
| [getKumimoji()](#getKumimoji--) | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Menentukan apakah tinggi teks harus dinormalisasi. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Menentukan apakah tinggi teks harus dinormalisasi. |
| [getProofDisabled()](#getProofDisabled--) | Menentukan apakah teks tidak perlu diperiksa. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Menentukan apakah teks tidak perlu diperiksa. |
| [getFontUnderline()](#getFontUnderline--) | Mengembalikan atau mengatur jenis underline teks. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Mengembalikan atau mengatur jenis underline teks. |
| [getTextCapType()](#getTextCapType--) | Mengembalikan atau mengatur jenis kapitalisasi teks. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Mengembalikan atau mengatur jenis kapitalisasi teks. |
| [getStrikethroughType()](#getStrikethroughType--) | Mengembalikan atau mengatur jenis coret teks. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Mengembalikan atau mengatur jenis coret teks. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. |
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
| [getLanguageId()](#getLanguageId--) | Mengembalikan atau mengatur Id bahasa proofing. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Mengembalikan atau mengatur Id bahasa proofing. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Mengembalikan atau mengatur Id bahasa alternatif. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Mengembalikan atau mengatur Id bahasa alternatif. |
| [getSpacing()](#getSpacing--) | Mengembalikan atau mengatur peningkatan spasi antar karakter. |
| [setSpacing(float value)](#setSpacing-float-) | Mengembalikan atau mengatur peningkatan spasi antar karakter. |
| [getSpellCheck()](#getSpellCheck--) | Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```


Mengembalikan properti LineFormat untuk outline teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Mengembalikan properti FillFormat teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Mengembalikan properti EffectFormat teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```


Mengembalikan warna yang digunakan untuk menyorot teks. Tidak ada pewarisan yang diterapkan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```


Mengembalikan properti LineFormat yang digunakan untuk menyorot garis bawah. Tidak ada pewarisan yang diterapkan. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```


Mengembalikan properti FillFormat garis bawah. Tidak ada pewarisan yang diterapkan. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```


Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```


Menentukan apakah font tebal. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```


Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```


Menentukan apakah font miring. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```


Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```


Menentukan apakah angka harus mengabaikan tata letak teks vertikal khusus bahasa timur. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```


Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```


Menentukan apakah tinggi teks harus dinormalisasi. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```


Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```


Menentukan apakah teks tidak perlu diperiksa. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Mengembalikan atau mengatur jenis underline teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Mengembalikan:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```


Mengembalikan atau mengatur jenis underline teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Mengembalikan atau mengatur jenis kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextCapType](../../com.aspose.slides/textcaptype).

**Mengembalikan:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```


Mengembalikan atau mengatur jenis kapitalisasi teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextCapType](../../com.aspose.slides/textcaptype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Mengembalikan atau mengatur jenis coret teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Mengembalikan:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```


Mengembalikan atau mengatur jenis coret teks. Tidak ada pewarisan yang diterapkan. Baca/tulis [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```


Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```


Menentukan apakah gaya underline memiliki properti LineFormat sendiri atau mewarisinya dari properti LineFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```


Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```


Menentukan apakah gaya underline memiliki properti FillFormat sendiri atau mewarisinya dari properti FillFormat teks. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Mengembalikan atau mengatur tinggi font pada bagian. **Float.NaN** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Mengembalikan:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```


Mengembalikan atau mengatur tinggi font pada bagian. **Float.NaN** berarti tinggi tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Mengembalikan atau mengatur info font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Mengembalikan atau mengatur info font Latin. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Mengembalikan atau mengatur info font Asia Timur. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Mengembalikan atau mengatur info font skrip kompleks. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Mengembalikan atau mengatur info font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```


Mengembalikan atau mengatur info font simbolik. Null berarti font tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Mengembalikan:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```


Mengembalikan atau mengatur teks superskrip atau subskrip. Nilai dari -100% (subskrip) hingga 100% (superskrip). **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Mengembalikan:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```


Mengembalikan atau mengatur ukuran font minimal, di mana kerning harus diaktifkan. **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Mengembalikan atau mengatur Id bahasa proofing. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```


Mengembalikan atau mengatur Id bahasa proofing. Digunakan untuk memeriksa ejaan dan tata bahasa. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Mengembalikan atau mengatur Id bahasa alternatif. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```


Mengembalikan atau mengatur Id bahasa alternatif. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Mengembalikan atau mengatur peningkatan spasi antar karakter. **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Mengembalikan:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```


Mengembalikan atau mengatur peningkatan spasi antar karakter. **Float.NaN** berarti nilai tidak terdefinisi dan harus diwarisi dari Master. Baca/tulis float.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```


Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini disetel ke false, pemeriksaan ejaan untuk elemen teks akan ditekan. Ketika disetel ke true, pemeriksaan ejaan diizinkan. Nilai default adalah false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Akses bagian teks pertama di dalam bentuk pertama pada slide pertama
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktifkan pemeriksaan ejaan untuk bagian teks ini
>      portion.getPortionFormat().setSpellCheck(true);
>      // Simpan presentasi yang telah dimodifikasi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```


Mengambil atau mengatur nilai yang menunjukkan apakah pemeriksaan ejaan diaktifkan untuk bagian teks. Ketika properti ini disetel ke false, pemeriksaan ejaan untuk elemen teks akan ditekan. Ketika disetel ke true, pemeriksaan ejaan diizinkan. Nilai default adalah false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Akses bagian teks pertama di dalam bentuk pertama pada slide pertama
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aktifkan pemeriksaan ejaan untuk bagian teks ini
>      portion.getPortionFormat().setSpellCheck(true);
>      // Simpan presentasi yang telah dimodifikasi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |