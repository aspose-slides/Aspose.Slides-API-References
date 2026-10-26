---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /id/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), semua properti kelas ini dapat ditulis.

--------------------

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam sebagian besar kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwariskan, Anda perlu menggunakan metode [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) yang mengembalikan sebuah instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBullet()](#getBullet--) | Mengembalikan format bullet paragraf. |
| [getDepth()](#getDepth--) | Mengembalikan atau mengatur kedalaman paragraf. |
| [setDepth(short value)](#setDepth-short-) | Mengembalikan atau mengatur kedalaman paragraf. |
| [getAlignment()](#getAlignment--) | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. |
| [setAlignment(int value)](#setAlignment-int-) | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. |
| [getSpaceWithin()](#getSpaceWithin--) | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. |
| [getSpaceBefore()](#getSpaceBefore--) | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. |
| [getSpaceAfter()](#getSpaceAfter--) | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Menentukan apakah pemecahan baris Asia Timur digunakan dalam paragraf. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Menentukan apakah pemecahan baris Asia Timur digunakan dalam paragraf. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah penulisan Right to Left digunakan dalam paragraf. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Menentukan apakah penulisan Right to Left digunakan dalam paragraf. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Menentukan apakah pemecahan baris Latin digunakan dalam paragraf. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Menentukan apakah pemecahan baris Latin digunakan dalam paragraf. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Menentukan apakah tanda baca gantung digunakan dalam paragraf. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Menentukan apakah tanda baca gantung digunakan dalam paragraf. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. |
| [setMarginRight(float value)](#setMarginRight-float-) | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. |
| [getIndent()](#getIndent--) | Mengembalikan atau mengatur Inden Baris Pertama/Inden Gantung paragraf tanpa pewarisan. |
| [setIndent(float value)](#setIndent-float-) | Mengembalikan atau mengatur Inden Baris Pertama/Inden Gantung paragraf tanpa pewarisan. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. |
| [getTabs()](#getTabs--) | Mengembalikan tabulasi paragraf. |
| [getFontAlignment()](#getFontAlignment--) | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Mengembalikan format bagian default paragraf. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan diterapkan. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Mengembalikan format bullet paragraf. Hanya-baca [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Mengembalikan:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Mengembalikan atau mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis short.

**Mengembalikan:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Mengembalikan atau mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis short.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [TextAlignment](../../com.aspose.slides/textalignment).

**Mengembalikan:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [TextAlignment](../../com.aspose.slides/textalignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan. Baca/tulis float.

**Mengembalikan:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif berarti ukuran dalam poin. Tidak ada pewarisan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis float.

**Mengembalikan:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis float.

**Mengembalikan:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Menentukan apakah pemecahan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Menentukan apakah pemecahan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Menentukan apakah penulisan Right to Left digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Menentukan apakah penulisan Right to Left digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Menentukan apakah pemecahan baris Latin digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Menentukan apakah pemecahan baris Latin digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis float.

**Mengembalikan:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis float.

**Mengembalikan:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Mengembalikan atau mengatur Inden Baris Pertama/Inden Gantung paragraf tanpa pewarisan. Inden Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis float.

**Mengembalikan:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Mengembalikan atau mengatur Inden Baris Pertama/Inden Gantung paragraf tanpa pewarisan. Inden Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis float.

**Mengembalikan:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Mengembalikan tabulasi paragraf. Tidak ada pewarisan. Hanya-baca [ITabCollection](../../com.aspose.slides/itabcollection).

**Mengembalikan:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [FontAlignment](../../com.aspose.slides/fontalignment).

**Mengembalikan:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Mengembalikan format bagian default paragraf. Tidak ada pewarisan. Hanya-baca [IPortionFormat](../../com.aspose.slides/iportionformat).

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).