---
title: BulletFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti format bullet paragraf.
type: docs
url: /id/com.aspose.slides/bulletformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Represents paragraph bullet formatting properties.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Mengembalikan atau mengatur tipe bullet dari paragraf tanpa pewarisan. |
| [setType(byte value)](#setType-byte-) | Mengembalikan atau mengatur tipe bullet dari paragraf tanpa pewarisan. |
| [getChar()](#getChar--) | Mengembalikan atau mengatur karakter bullet dari paragraf tanpa pewarisan. |
| [setChar(char value)](#setChar-char-) | Mengembalikan atau mengatur karakter bullet dari paragraf tanpa pewarisan. |
| [getFont()](#getFont--) | Mengembalikan atau mengatur font bullet dari paragraf tanpa pewarisan. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font bullet dari paragraf tanpa pewarisan. |
| [getHeight()](#getHeight--) | Mengembalikan atau mengatur tinggi bullet dari paragraf tanpa pewarisan. |
| [setHeight(float value)](#setHeight-float-) | Mengembalikan atau mengatur tinggi bullet dari paragraf tanpa pewarisan. |
| [getColor()](#getColor--) | Mengembalikan format warna bullet dari paragraf tanpa pewarisan. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan. |
| [isBulletHardColor()](#isBulletHardColor--) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [isBulletHardFont()](#isBulletHardFont--) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [getPicture()](#getPicture--) | Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa pewarisan. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Mengatur pergeseran non-zero default untuk Indent paragraf efektif dan MarginLeft ketika bullet diaktifkan (seperti yang dilakukan PowerPoint bila mengaktifkan bullet/penomoran paragraf). |
| [getEffective()](#getEffective--) | Mendapatkan data format bullet efektif dengan pewarisan yang diterapkan. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Mengembalikan atau mengatur tipe bullet dari paragraf tanpa pewarisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Mengembalikan:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Mengembalikan atau mengatur tipe bullet dari paragraf tanpa pewarisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

Mengembalikan atau mengatur karakter bullet dari paragraf tanpa pewarisan. Baca/tulis char .

**Mengembalikan:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Mengembalikan atau mengatur karakter bullet dari paragraf tanpa pewarisan. Baca/tulis char .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

Mengembalikan atau mengatur font bullet dari paragraf tanpa pewarisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Mengembalikan atau mengatur font bullet dari paragraf tanpa pewarisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Mengembalikan atau mengatur tinggi bullet dari paragraf tanpa pewarisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float .

--------------------

Nilai tinggi negatif berarti tinggi diberikan dalam poin dan nilai positif berarti tinggi berupa persentase dari teks di sekitarnya.

**Mengembalikan:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Mengembalikan atau mengatur tinggi bullet dari paragraf tanpa pewarisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float .

--------------------

Nilai tinggi negatif berarti tinggi diberikan dalam poin dan nilai positif berarti tinggi berupa persentase dari teks di sekitarnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Mengembalikan format warna bullet dari paragraf tanpa pewarisan. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. Baca/tulis short .

**Mengembalikan:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. Baca/tulis short .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Mengembalikan:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

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

Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa pewarisan. Baca-saja [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Mengembalikan:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Mengatur pergeseran non-zero default untuk Indent paragraf efektif dan MarginLeft ketika bullet diaktifkan (seperti yang dilakukan PowerPoint bila mengaktifkan bullet/penomoran paragraf). Jika bullet dinonaktifkan maka cukup mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint bila menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan berdasarkan konteks bullet saat ini - IBulletFormat.Type, .NumberedBulletStyle, dan FontHeight dari bagian pertama. Pergeseran indent non-zero diterapkan pada Indent dan MarginLeft efektif dari paragraf saat ini (menjadikan nilai hasil sebagai nilai lokal).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Mendapatkan data format bullet efektif dengan pewarisan yang diterapkan.

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

Versi. Baca-saja long.

**Mengembalikan:**
long