---
title: ITextStyle
second_title: Aspose.Slides untuk Android via Java API Reference
description: Properti pemformatan gaya teks.
type: docs
url: /id/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Properti pemformatan gaya teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | If level of style exist returns it, otherwise returns null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Default paragraph propertiies. |
| [getEffective()](#getEffective--) | Gets effective text style formatting data with the inheritance applied. |
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

Properti default paragraf. Hanya-baca [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Mendapatkan data pemformatan gaya teks yang efektif dengan penerapan pewarisan.

**Mengembalikan:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Sebuah [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).