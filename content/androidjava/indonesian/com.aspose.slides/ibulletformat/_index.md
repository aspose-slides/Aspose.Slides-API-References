---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /id/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Mewakili properti format bullet paragraf.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan atau mengatur jenis bullet pada paragraf tanpa pewarisan. |
| [setType(byte value)](#setType-byte-) | Mengembalikan atau mengatur jenis bullet pada paragraf tanpa pewarisan. |
| [getChar()](#getChar--) | Mengembalikan atau mengatur karakter bullet pada paragraf tanpa pewarisan. |
| [setChar(char value)](#setChar-char-) | Mengembalikan atau mengatur karakter bullet pada paragraf tanpa pewarisan. |
| [getFont()](#getFont--) | Mengembalikan atau mengatur font bullet pada paragraf tanpa pewarisan. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font bullet pada paragraf tanpa pewarisan. |
| [getHeight()](#getHeight--) | Mengembalikan atau mengatur tinggi bullet pada paragraf tanpa pewarisan. |
| [setHeight(float value)](#setHeight-float-) | Mengembalikan atau mengatur tinggi bullet pada paragraf tanpa pewarisan. |
| [getColor()](#getColor--) | Mengembalikan format warna bullet pada paragraf tanpa pewarisan. |
| [getPicture()](#getPicture--) | Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa pewarisan. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Mengembalikan atau mengatur gaya bullet bernomor dengan tanpa pewarisan. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Mengembalikan atau mengatur gaya bullet bernomor dengan tanpa pewarisan. |
| [isBulletHardColor()](#isBulletHardColor--) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [isBulletHardFont()](#isBulletHardFont--) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Mengatur pergeseran non-zero default untuk Indent dan MarginLeft paragraf yang efektif ketika bullets diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). |
| [getEffective()](#getEffective--) | Mendapatkan data format bullet yang efektif dengan pewarisan diterapkan. |
### getType() {#getType--}
```
public abstract byte getType()
```


Mengembalikan atau mengatur jenis bullet pada paragraf tanpa pewarisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Mengembalikan:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Mengembalikan atau mengatur jenis bullet pada paragraf tanpa pewarisan. Baca/tulis [BulletType](../../com.aspose.slides/bullettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```


Mengembalikan atau mengatur karakter bullet pada paragraf tanpa pewarisan. Baca/tulis char.

**Mengembalikan:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Mengembalikan atau mengatur karakter bullet pada paragraf tanpa pewarisan. Baca/tulis char.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Mengembalikan atau mengatur font bullet pada paragraf tanpa pewarisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Mengembalikan atau mengatur font bullet pada paragraf tanpa pewarisan. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Mengembalikan atau mengatur tinggi bullet pada paragraf tanpa pewarisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float.

**Mengembalikan:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Mengembalikan atau mengatur tinggi bullet pada paragraf tanpa pewarisan. Nilai Float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Mengembalikan format warna bullet pada paragraf tanpa pewarisan. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa pewarisan. Baca-saja [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Mengembalikan:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. Baca/tulis short.

**Mengembalikan:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Mengembalikan atau mengatur angka pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan. Baca/tulis short.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Mengembalikan atau mengatur gaya bullet bernomor dengan tanpa pewarisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Mengembalikan:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Mengembalikan atau mengatur gaya bullet bernomor dengan tanpa pewarisan. Baca/tulis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool#True** jika bullet memiliki warna sendiri dan **NullableBool#False** jika bullet mewarisi warna dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool#True** jika bullet memiliki warna sendiri dan **NullableBool#False** jika bullet mewarisi warna dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool#True** jika bullet memiliki font sendiri dan **NullableBool#False** jika bullet mewarisi font dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. **NullableBool#True** jika bullet memiliki font sendiri dan **NullableBool#False** jika bullet mewarisi font dari bagian pertama dalam paragraf. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Mengatur pergeseran non-zero default untuk Indent dan MarginLeft paragraf yang efektif ketika bullets diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). Jika bullets dinonaktifkan, cukup reset Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan berdasarkan konteks bullet saat ini – IBulletFormat.Type, .NumberedBulletStyle dan FontHeight bagian pertama. Pergeseran indent non-zero diterapkan pada Indent dan MarginLeft efektif paragraf saat ini (membuat nilai hasil menjadi nilai lokal).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Mendapatkan data format bullet yang efektif dengan pewarisan diterapkan.

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).