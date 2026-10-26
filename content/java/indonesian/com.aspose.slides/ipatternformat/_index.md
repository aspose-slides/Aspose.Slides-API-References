---
title: IPatternFormat
second_title: Aspose.Slides untuk Java Referensi API
description: Mewakili pola untuk mengisi sebuah bentuk.
type: docs
url: /id/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Mewakili pola untuk mengisi sebuah bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Mendapatkan atau mengatur gaya pola. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Mendapatkan atau mengatur gaya pola. |
| [getForeColor()](#getForeColor--) | Mengembalikan warna pola latar depan. |
| [getBackColor()](#getBackColor--) | Mengembalikan warna pola latar belakang. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Membuat gambar ubin untuk pengisian pola. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Mendapatkan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Mengembalikan:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Mendapatkan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Mengembalikan warna pola latar depan. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Mengembalikan warna pola latar belakang. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.awt.Color | Warna java.awt.Color latar belakang untuk pola. |
| foreground | java.awt.Color | Warna java.awt.Color latar depan untuk pola. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Membuat gambar ubin untuk pengisian pola.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.awt.Color | Warna java.awt.Color default, didefinisikan dalam objek StyleEx milik ShapeEx. Warna isi dapat bergantung pada ini. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin java.awt.image.BufferedImage.