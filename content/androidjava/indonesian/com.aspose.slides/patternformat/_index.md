---
title: PatternFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Membuat gambar ubin untuk pengisian pola. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Returns:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Mengembalikan warna pola latar depan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Mengembalikan warna pola latar belakang. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer latar belakang untuk pola. |
| foreground | java.lang.Integer | java.lang.Integer latar depan untuk pola. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Ubin [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Membuat gambar ubin untuk pengisian pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer default |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Ubin [IImage](../../com.aspose.slides/iimage).