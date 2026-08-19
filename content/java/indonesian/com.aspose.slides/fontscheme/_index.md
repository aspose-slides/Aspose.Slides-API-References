---
title: FontScheme
second_title: Referensi API Aspose.Slides untuk Java
description: Menyimpan font yang didefinisikan dalam tema.
type: docs
url: /id/com.aspose.slides/fontscheme/
---
**Pewarisan:**
java.lang.Object

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

Menyimpan font yang didefinisikan dalam tema.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMinor()](#getMinor--) | Mengembalikan koleksi font untuk bagian "body" pada slide. |
| [getMajor()](#getMajor--) | Mengembalikan koleksi font untuk bagian "heading" pada slide. |
| [getName()](#getName--) | Mengembalikan nama skema font. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan nama skema font. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

Mengembalikan koleksi font untuk bagian "body" pada slide. Hanya-baca [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

Mengembalikan koleksi font untuk bagian "heading" pada slide. Hanya-baca [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```

Mengembalikan nama skema font. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Mengembalikan nama skema font. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject