---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Properti format gaya teks.
type: docs
url: /id/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Properti format gaya teks.

## Metode

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Jika level gaya ada, mengembalikannya; jika tidak, mengembalikan null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Properti paragraf default. |
| [getEffective()](#getEffective--) | Mendapatkan data format gaya teks yang efektif dengan penerapan pewarisan. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Jika level gaya ada, mengembalikannya; jika tidak, mengembalikan null.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari level. Harus berada dalam interval 0..8. |

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Pemformatan level [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Properti paragraf default. Baca-saja [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Mendapatkan data format gaya teks yang efektif dengan penerapan pewarisan.

**Mengembalikan:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - sebuah [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).