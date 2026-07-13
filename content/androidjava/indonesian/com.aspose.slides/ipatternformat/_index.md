---
title: IPatternFormat
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili pola untuk mengisi bentuk.
type: docs
url: /id/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Mewakili pola untuk mengisi bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Mengembalikan atau mengatur gaya pola. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Mengembalikan atau mengatur gaya pola. |
| [getForeColor()](#getForeColor--) | Mengembalikan warna pola latar depan. |
| [getBackColor()](#getBackColor--) | Mengembalikan warna pola latar belakang. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Membuat gambar ubin untuk pengisian pola. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

**Mengembalikan:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Mengembalikan atau mengatur gaya pola. Baca/tulis [PatternStyle](../../com.aspose.slides/patternstyle).

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
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer latar belakang untuk pola. |
| foreground | java.lang.Integer | java.lang.Integer latar depan untuk pola. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Membuat gambar ubin untuk pengisian pola.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | java.lang.Integer | java.lang.Integer default, yang didefinisikan dalam objek StyleEx milik ShapeEx. Warna pengisian dapat bergantung pada ini. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin android.graphics.Bitmap.