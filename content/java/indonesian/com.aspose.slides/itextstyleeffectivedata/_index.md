---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objek tidak dapat diubah yang berisi properti gaya teks efektif.
type: docs
url: /id/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objek tidak dapat diubah yang berisi properti gaya teks efektif.

--------------------

Antarmuka ini digunakan bersama dengan antarmuka [ITextStyle](../../com.aspose.slides/itextstyle) untuk mengembalikan nilai format efektif dengan penerapan pewarisan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Mengembalikan level gaya efektif. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Mengembalikan properti paragraf default yang efektif. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Mengembalikan level gaya efektif.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol untuk level. Harus berada dalam interval 0..8. |

**Mengembalikan:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Pemformatan efektif pada level [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Mengembalikan properti paragraf default yang efektif. Hanya-baca [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Mengembalikan:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)