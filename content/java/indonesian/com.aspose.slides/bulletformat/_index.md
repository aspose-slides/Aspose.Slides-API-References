---
title: BulletFormat
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili properti pemformatan bullet paragraf.
type: docs
url: /id/com.aspose.slides/bulletformat/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Mewakili properti pemformatan bullet paragraf.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan atau mengatur tipe bullet dari sebuah paragraf tanpa warisan. |
| [setType(byte value)](#setType-byte-) | Mengembalikan atau mengatur tipe bullet dari sebuah paragraf tanpa warisan. |
| [getChar()](#getChar--) | Mengembalikan atau mengatur karakter bullet dari sebuah paragraf tanpa warisan. |
| [setChar(char value)](#setChar-char-) | Mengembalikan atau mengatur karakter bullet dari sebuah paragraf tanpa warisan. |
| [getFont()](#getFont--) | Mengembalikan atau mengatur font bullet dari sebuah paragraf tanpa warisan. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font bullet dari sebuah paragraf tanpa warisan. |
| [getHeight()](#getHeight--) | Mengembalikan atau mengatur tinggi bullet dari sebuah paragraf tanpa warisan. |
| [setHeight(float value)](#setHeight-float-) | Mengembalikan atau mengatur tinggi bullet dari sebuah paragraf tanpa warisan. |
| [getColor()](#getColor--) | Mengembalikan format warna bullet dari sebuah paragraf tanpa warisan. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa warisan. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa warisan. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Mengembalikan atau mengatur gaya bullet bernomor tanpa warisan. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Mengembalikan atau mengatur gaya bullet bernomor tanpa warisan. |
| [isBulletHardColor()](#isBulletHardColor--) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [isBulletHardFont()](#isBulletHardFont--) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [getPicture()](#getPicture--) | Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa warisan. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Mengatur pergeseran default non-zero untuk Indent paragraf yang efektif dan MarginLeft ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan bullet yang efektif dengan warisan yang diterapkan. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```


Mengembalikan atau mengatur tipe bullet dari sebuah paragraf tanpa warisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Mengembalikan:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Mengembalikan atau mengatur tipe bullet dari sebuah paragraf tanpa warisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Mengembalikan atau mengatur karakter bullet dari sebuah paragraf tanpa warisan. Baca/tulis char .

**Mengembalikan:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Mengembalikan atau mengatur karakter bullet dari sebuah paragraf tanpa warisan. Baca/tulis char .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Mengembalikan atau mengatur font bullet dari sebuah paragraf tanpa warisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Mengembalikan atau mengatur font bullet dari sebuah paragraf tanpa warisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Mengembalikan atau mengatur tinggi bullet dari sebuah paragraf tanpa warisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float .

--------------------

Nilai tinggi negatif berarti tinggi diberikan dalam poin dan nilai positif berarti tinggi adalah persentase dari teks di sekitarnya.

**Mengembalikan:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Mengembalikan atau mengatur tinggi bullet dari sebuah paragraf tanpa warisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float .

--------------------

Nilai tinggi negatif berarti tinggi diberikan dalam poin dan nilai positif berarti tinggi adalah persentase dari teks di sekitarnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Mengembalikan format warna bullet dari sebuah paragraf tanpa warisan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa warisan. Baca/tulis short .

**Mengembalikan:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa warisan. Baca/tulis short .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Mengembalikan atau mengatur gaya bullet bernomor tanpa warisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Mengembalikan:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Mengembalikan atau mengatur gaya bullet bernomor tanpa warisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool.True** jika bullet memiliki warna sendiri dan **NullableBool.False** jika bullet mewarisi warna dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool.True** jika bullet memiliki warna sendiri dan **NullableBool.False** jika bullet mewarisi warna dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool.True** jika bullet memiliki font sendiri dan **NullableBool.False** jika bullet mewarisi font dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool.True** jika bullet memiliki font sendiri dan **NullableBool.False** jika bullet mewarisi font dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa warisan. Hanya-baca [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Mengembalikan:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Mengatur pergeseran default non-zero untuk Indent paragraf yang efektif dan MarginLeft ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). Jika bullet dinonaktifkan, cukup mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan terkait konteks bullet saat ini – IBulletFormat.Type, .NumberedBulletStyle dan FontHeight bagian pertama. Pergeseran indent non-zero diterapkan pada Indent dan MarginLeft efektif paragraf saat ini (menjadikan nilai hasil sebagai nilai lokal).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Mendapatkan data pemformatan bullet yang efektif dengan warisan yang diterapkan.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Sebuah [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long