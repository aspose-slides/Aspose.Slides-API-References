---
title: ILineFormatEffectiveData
second_title: Referensi API Java Aspose.Slides untuk Android
description: Objek yang tidak dapat diubah yang berisi properti pemformatan garis yang efektif.
type: docs
url: /id/com.aspose.slides/ilineformateffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Objek tak dapat diubah yang berisi properti pemformatan garis yang efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [ILineFormat](../../com.aspose.slides/ilineformat) untuk mengembalikan nilai pemformatan yang efektif dengan penerapan warisan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Mengembalikan format isian sebuah garis. |
| [getSketchFormat()](#getSketchFormat--) | Mengembalikan format sketsa sebuah garis. |
| [getWidth()](#getWidth--) | Mengembalikan lebar sebuah garis. |
| [getDashStyle()](#getDashStyle--) | Mengembalikan gaya dash garis. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Mengembalikan pola dash khusus. |
| [getCapStyle()](#getCapStyle--) | Mengembalikan gaya cap garis. |
| [getStyle()](#getStyle--) | Mengembalikan gaya garis. |
| [getAlignment()](#getAlignment--) | Mengembalikan perataan garis. |
| [getJoinStyle()](#getJoinStyle--) | Mengembalikan gaya sambungan garis. |
| [getMiterLimit()](#getMiterLimit--) | Mengembalikan batas miter sebuah garis. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Mengembalikan gaya kepala panah di awal sebuah garis. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Mengembalikan gaya kepala panah di akhir sebuah garis. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Mengembalikan lebar kepala panah di awal sebuah garis. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Mengembalikan lebar kepala panah di akhir sebuah garis. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Mengembalikan panjang kepala panah di awal sebuah garis. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Mengembalikan panjang kepala panah di akhir sebuah garis. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Menentukan apakah dua instance ILineFormatEffectiveData sama. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Mengembalikan format isian sebuah garis. Hanya-baca [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Mengembalikan:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Mengembalikan format sketsa sebuah garis. Hanya-baca [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Mengembalikan:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Mengembalikan lebar sebuah garis. Hanya-baca double.

**Mengembalikan:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Mengembalikan gaya dash garis. Hanya-baca [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Mengembalikan:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Mengembalikan pola dash khusus. Hanya-baca float[].

**Mengembalikan:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Mengembalikan gaya cap garis. Hanya-baca [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Mengembalikan:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Mengembalikan gaya garis. Hanya-baca [LineStyle](../../com.aspose.slides/linestyle).

**Mengembalikan:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Mengembalikan perataan garis. Hanya-baca [LineAlignment](../../com.aspose.slides/linealignment).

**Mengembalikan:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Mengembalikan gaya sambungan garis. Hanya-baca [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Mengembalikan:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Mengembalikan batas miter sebuah garis. Hanya-baca float.

**Mengembalikan:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Mengembalikan gaya kepala panah di awal sebuah garis. Hanya-baca [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Mengembalikan gaya kepala panah di akhir sebuah garis. Hanya-baca [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Mengembalikan lebar kepala panah di awal sebuah garis. Hanya-baca [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Mengembalikan lebar kepala panah di akhir sebuah garis. Hanya-baca [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Mengembalikan panjang kepala panah di awal sebuah garis. Hanya-baca [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Mengembalikan panjang kepala panah di akhir sebuah garis. Hanya-baca [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Menentukan apakah dua instance ILineFormatEffectiveData sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData yang dibandingkan dengan ILineFormatEffectiveData saat ini. |

**Mengembalikan:**
boolean - **true** jika ILineFormatEffectiveData yang ditentukan sama dengan ILineFormatEffectiveData saat ini; sebaliknya, **false**.