---
title: PatternFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili pola untuk mengisi sebuah bentuk.
type: docs
url: /id/com.aspose.slides/patternformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Mewakili pola untuk mengisi sebuah bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Mengembalikan atau mengatur gaya pola. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Mengembalikan atau mengatur gaya pola. |
| [getForeColor()](#getForeColor--) | Mengembalikan warna pola latar depan. |
| [getBackColor()](#getBackColor--) | Mengembalikan warna pola latar belakang. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Membuat gambar ubin untuk isi pola dengan warna yang ditentukan. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Membuat gambar ubin untuk isi pola. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Mengembalikan:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Mengembalikan warna pola latar depan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Mengembalikan warna pola latar belakang. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```


Membuat gambar ubin untuk isi pola dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.awt.Color | Warna latar belakang java.awt.Color untuk pola. |
| foreground | java.awt.Color | Warna latar depan java.awt.Color untuk pola. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```


Membuat gambar ubin untuk isi pola.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.awt.Color | Warna default java.awt.Color |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).