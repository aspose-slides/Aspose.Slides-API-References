---
title: LineFormat
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili format sebuah garis.
type: docs
url: /id/com.aspose.slides/lineformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Mewakili format garis.
## Methods

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Mengembalikan true jika format garis tidak didefinisikan (seperti baru dibuat, default). |
| [getFillFormat()](#getFillFormat--) | Mengembalikan format isi dari sebuah garis. |
| [getSketchFormat()](#getSketchFormat--) | Mengembalikan format sketsa dari sebuah garis. |
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
| [getMiterLimit()](#getMiterLimit--) | Mengembalikan atau mengatur batas miter suatu garis. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Mengembalikan atau mengatur batas miter suatu garis. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Mengembalikan atau mengatur gaya kepala panah di awal garis. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Mengembalikan atau mengatur gaya kepala panah di awal garis. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Mengembalikan atau mengatur gaya kepala panah di akhir garis. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Mengembalikan atau mengatur gaya kepala panah di akhir garis. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Mengembalikan atau mengatur lebar kepala panah di awal garis. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Mengembalikan atau mengatur lebar kepala panah di awal garis. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Mengembalikan atau mengatur lebar kepala panah di akhir garis. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Mengembalikan atau mengatur lebar kepala panah di akhir garis. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Mengembalikan atau mengatur panjang kepala panah di awal garis. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Mengembalikan atau mengatur panjang kepala panah di awal garis. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Mengembalikan atau mengatur panjang kepala panah di akhir garis. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Mengembalikan atau mengatur panjang kepala panah di akhir garis. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Menentukan apakah dua instance LineFormat sama. |
| [getEffective()](#getEffective--) | Mendapatkan data format garis yang efektif dengan pewarisan diterapkan. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Membandingkan dengan objek yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Mengembalikan:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Mengembalikan true jika format garis tidak didefinisikan (seperti baru dibuat, default). Hanya-baca boolean .

**Mengembalikan:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Mengembalikan format isi dari sebuah garis. Hanya-baca [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Mengembalikan:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Mengembalikan format sketsa dari sebuah garis. Hanya-baca [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Mengembalikan:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mengembalikan atau mengatur lebar sebuah garis. Baca/tulis double .

**Mengembalikan:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengembalikan atau mengatur lebar sebuah garis. Baca/tulis double .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Mengembalikan atau mengatur gaya dash garis. Baca/tulis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Mengembalikan:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Mengembalikan atau mengatur gaya dash garis. Baca/tulis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Mengembalikan atau mengatur pola dash khusus. Baca/tulis float[] .

**Mengembalikan:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Mengembalikan atau mengatur pola dash khusus. Baca/tulis float[] .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Mengembalikan atau mengatur gaya cap garis. Baca/tulis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Mengembalikan:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Mengembalikan atau mengatur gaya cap garis. Baca/tulis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Mengembalikan atau mengatur gaya garis. Baca/tulis [LineStyle](../../com.aspose.slides/linestyle).

**Mengembalikan:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Mengembalikan atau mengatur gaya garis. Baca/tulis [LineStyle](../../com.aspose.slides/linestyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Mengembalikan atau mengatur perataan garis. Baca/tulis [LineAlignment](../../com.aspose.slides/linealignment).

**Mengembalikan:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Mengembalikan atau mengatur perataan garis. Baca/tulis [LineAlignment](../../com.aspose.slides/linealignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Mengembalikan atau mengatur gaya sambungan garis. Baca/tulis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Mengembalikan:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Mengembalikan atau mengatur gaya sambungan garis. Baca/tulis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Mengembalikan atau mengatur batas miter suatu garis. Baca/tulis float .

**Mengembalikan:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Mengembalikan atau mengatur batas miter suatu garis. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Mengembalikan atau mengatur gaya kepala panah di awal garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Mengembalikan atau mengatur gaya kepala panah di awal garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Mengembalikan atau mengatur gaya kepala panah di akhir garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Mengembalikan:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Mengembalikan atau mengatur gaya kepala panah di akhir garis. Baca/tulis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Mengembalikan atau mengatur lebar kepala panah di awal garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Mengembalikan atau mengatur lebar kepala panah di awal garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Mengembalikan atau mengatur lebar kepala panah di akhir garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Mengembalikan:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Mengembalikan atau mengatur lebar kepala panah di akhir garis. Baca/tulis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Mengembalikan atau mengatur panjang kepala panah di awal garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Mengembalikan atau mengatur panjang kepala panah di awal garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Mengembalikan atau mengatur panjang kepala panah di akhir garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Mengembalikan:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Mengembalikan atau mengatur panjang kepala panah di akhir garis. Baca/tulis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


Menentukan apakah dua instance LineFormat sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat untuk dibandingkan dengan LineFormat saat ini. |

**Mengembalikan:**
boolean - **true** jika LineFormat yang ditentukan sama dengan LineFormat saat ini; lainnya, **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


Mendapatkan data format garis yang efektif dengan pewarisan diterapkan.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).