---
title: ILineFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili format sebuah garis.
type: docs
url: /id/com.aspose.slides/ilineformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Mewakili format sebuah garis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Mengembalikan true jika format garis tidak ditentukan (seperti baru dibuat, default). |
| [getFillFormat()](#getFillFormat--) | Mengembalikan format isi sebuah garis. |
| [getSketchFormat()](#getSketchFormat--) | Mengembalikan format sketsa sebuah garis. |
| [getWidth()](#getWidth--) | Mengembalikan atau mengatur lebar sebuah garis. |
| [setWidth(double value)](#setWidth-double-) | Mengembalikan atau mengatur lebar sebuah garis. |
| [getDashStyle()](#getDashStyle--) | Mengembalikan atau mengatur gaya dash garis. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Mengembalikan atau mengatur gaya dash garis. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Mengembalikan atau mengatur pola dash khusus. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Mengembalikan atau mengatur pola dash khusus. |
| [getCapStyle()](#getCapStyle--) | Mengembalikan atau mengatur gaya cap garis. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Mengembalikan atau mengatur gaya cap garis. |
| [getStyle()](#getStyle--) | Mengembalikan atau mengatur gaya garis. |
| [setStyle(byte value)](#setStyle-byte-) | Mengembalikan atau mengatur gaya garis. |
| [getAlignment()](#getAlignment--) | Mengembalikan atau mengatur perataan garis. |
| [setAlignment(byte value)](#setAlignment-byte-) | Mengembalikan atau mengatur perataan garis. |
| [getJoinStyle()](#getJoinStyle--) | Mengembalikan atau mengatur gaya sambungan garis. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Mengembalikan atau mengatur gaya sambungan garis. |
| [getMiterLimit()](#getMiterLimit--) | Mengembalikan atau mengatur batas miter sebuah garis. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Mengembalikan atau mengatur batas miter sebuah garis. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Mengembalikan atau mengatur gaya ujung panah di awal sebuah garis. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Mengembalikan atau mengatur gaya ujung panah di awal sebuah garis. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Mengembalikan atau mengatur gaya ujung panah di akhir sebuah garis. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Mengembalikan atau mengatur gaya ujung panah di akhir sebuah garis. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Mengembalikan atau mengatur lebar ujung panah di awal sebuah garis. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Mengembalikan atau mengatur lebar ujung panah di awal sebuah garis. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Mengembalikan atau mengatur lebar ujung panah di akhir sebuah garis. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Mengembalikan atau mengatur lebar ujung panah di akhir sebuah garis. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Mengembalikan atau mengatur panjang ujung panah di awal sebuah garis. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Mengembalikan atau mengatur panjang ujung panah di awal sebuah garis. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Mengembalikan atau mengatur panjang ujung panah di akhir sebuah garis. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Mengembalikan atau mengatur panjang ujung panah di akhir sebuah garis. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Menentukan apakah dua instance LineFormat sama. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan garis yang efektif dengan pewarisan yang diterapkan. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Mengembalikan true jika format garis tidak ditentukan (seperti baru dibuat, default). Baca-saja boolean.

**Mengembalikan:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Mengembalikan format isi sebuah garis. Baca-saja [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Mengembalikan:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Mengembalikan format sketsa sebuah garis. Baca-saja [ISketchFormat](../../com.aspose.slides/isketchformat).

**Mengembalikan:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Mengembalikan atau mengatur lebar sebuah garis. Baca/tulis double.

**Mengembalikan:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Mengembalikan atau mengatur lebar sebuah garis. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Mengembalikan atau mengatur gaya dash garis. Baca/tulis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Mengembalikan:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Mengembalikan atau mengatur gaya dash garis. Baca/tulis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Mengembalikan atau mengatur pola dash khusus. Baca/tulis float[].

**Mengembalikan:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Mengembalikan atau mengatur pola dash khusus. Baca/tulis float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Mengembalikan atau mengatur gaya cap garis. Baca/tulis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Mengembalikan:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Mengembalikan atau mengatur gaya cap garis. Baca/tulis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Mengembalikan atau mengatur gaya garis. Baca/tulis [LineStyle](../../com.aspose.slides/linestyle).

**Mengembalikan:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Mengembalikan atau mengatur gaya garis. Baca/tulis [LineStyle](../../com.aspose.slides/linestyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Mengembalikan atau mengatur perataan garis. Baca/tulis [LineAlignment](../../com.aspose.slides/linealignment).

**Mengembalikan:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Mengembalikan atau mengatur perataan garis. Baca/tulis [LineAlignment](../../com.aspose.slides/linealignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Mengembalikan atau mengatur gaya sambungan garis. Baca/tulis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Mengembalikan:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Mengembalikan atau mengatur gaya sambungan garis. Baca/tulis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Mengembalikan atau mengatur batas miter sebuah garis. Baca/tulis float.

**Mengembalikan:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Mengembalikan atau mengatur batas miter sebuah garis. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Mengembalikan atau mengatur gaya ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Mengembalikan atau mengatur gaya ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Mengembalikan atau mengatur gaya ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Mengembalikan atau mengatur gaya ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Mengembalikan atau mengatur lebar ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Mengembalikan atau mengatur lebar ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Mengembalikan atau mengatur lebar ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Mengembalikan atau mengatur lebar ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Mengembalikan atau mengatur panjang ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Mengembalikan atau mengatur panjang ujung panah di awal sebuah garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Mengembalikan atau mengatur panjang ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Mengembalikan atau mengatur panjang ujung panah di akhir sebuah garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Menentukan apakah dua instance LineFormat sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat untuk dibandingkan dengan LineFormat saat ini. |

**Mengembalikan:**
boolean - **true** jika LineFormat yang ditentukan sama dengan LineFormat saat ini; sebaliknya, **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan garis yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Sebuah [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).