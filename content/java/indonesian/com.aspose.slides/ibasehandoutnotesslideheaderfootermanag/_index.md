---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili manajer yang menyimpan perilaku placeholder, termasuk placeholder header untuk semua jenis slide handout dan notes.
type: docs
url: /id/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Mewakili manajer yang memegang perilaku placeholder, termasuk placeholder header untuk semua tipe slide handout dan notes.

--------------------

Original interface name "IBaseHandoutNotesSlideHeaderFooterManager" is trancuted to "IBaseHandoutNotesSlideHeaderFooterManag" for COM compatibility (type name length must be not more than 39).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder header ada. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Mengubah visibilitas placeholder header slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Menetapkan teks ke placeholder header slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Mendapatkan nilai yang menunjukkan bahwa placeholder header ada. Baca boolean.

**Mengembalikan:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder header slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder header terlihat, sebaliknya - menyembunyikannya. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Menetapkan teks ke placeholder header slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |