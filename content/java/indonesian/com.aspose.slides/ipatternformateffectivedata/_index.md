---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides untuk Java API Referensi
description: Objek tak dapat diubah yang berisi properti pengisian pola yang efektif.
type: docs
url: /id/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objek tak dapat diubah yang berisi properti pengisian pola yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) dan [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Mengembalikan gaya pola. |
| [getForeColor()](#getForeColor--) | Mengembalikan warna pola latar depan. |
| [getBackColor()](#getBackColor--) | Mengembalikan warna pola latar belakang. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Mengembalikan gaya pola. Hanya-baca [PatternStyle](../../com.aspose.slides/patternstyle).

**Mengembalikan:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Mengembalikan warna pola latar depan. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Mengembalikan warna pola latar belakang. Hanya-baca java.awt.Color.

**Mengembalikan:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.awt.Color | Warna java.awt.Color latar belakang untuk pola. |
| foreground | java.awt.Color | Warna java.awt.Color latar depan untuk pola. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin [IImage](../../com.aspose.slides/iimage).