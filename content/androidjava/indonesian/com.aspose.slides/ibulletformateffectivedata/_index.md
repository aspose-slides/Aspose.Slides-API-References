---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objek tak dapat diubah yang berisi properti pemformatan bullet paragraf yang efektif.
type: docs
url: /id/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Objek tak dapat diubah yang berisi properti pemformatan bullet paragraf yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe bullet dari sebuah paragraf. |
| [getChar()](#getChar--) | Mengembalikan karakter bullet dari sebuah paragraf. |
| [getActualBulletValue()](#getActualBulletValue--) | Mengembalikan nilai bullet aktual untuk paragraf induk. |
| [getFont()](#getFont--) | Mengembalikan font bullet dari sebuah paragraf. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi bullet dari sebuah paragraf. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Mengembalikan angka pertama yang digunakan untuk kelompok bullet bernomor. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Mengembalikan gaya bullet bernomor. |
| [isBulletHardColor()](#isBulletHardColor--) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [isBulletHardFont()](#isBulletHardFont--) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. |
| [getPicture()](#getPicture--) | Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan format isian bullet dari sebuah paragraf. |
### getType() {#getType--}
```
public abstract byte getType()
```


Mengembalikan tipe bullet dari sebuah paragraf. Hanya baca [BulletType](../../com.aspose.slides/bullettype).

**Mengembalikan:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Mengembalikan karakter bullet dari sebuah paragraf. Hanya baca char.

**Mengembalikan:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Mengembalikan nilai bullet aktual untuk paragraf induk. Hanya baca String.

**Mengembalikan:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Mengembalikan font bullet dari sebuah paragraf. Hanya baca [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Mengembalikan tinggi bullet dari sebuah paragraf. Hanya baca float.

**Mengembalikan:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Mengembalikan angka pertama yang digunakan untuk kelompok bullet bernomor. Hanya baca short.

**Mengembalikan:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Mengembalikan gaya bullet bernomor. Hanya baca [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Mengembalikan:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf. Mengembalikan **true** jika bullet memiliki warna sendiri dan **false** jika bullet mewarisi warna dari bagian pertama dalam paragraf. Hanya baca boolean.

**Mengembalikan:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf. Mengembalikan **true** jika bullet memiliki font sendiri dan **true** jika bullet mewarisi font dari bagian pertama dalam paragraf. Hanya baca boolean.

**Mengembalikan:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf. Hanya baca [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Mengembalikan:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Mengembalikan format isian bullet dari sebuah paragraf. Hanya baca [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Anggap bahwa bentuk pertama pada slide pertama adalah AutoShape dengan beberapa teks...
>      // Keluarkan informasi tentang bullet paragraf teks
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)