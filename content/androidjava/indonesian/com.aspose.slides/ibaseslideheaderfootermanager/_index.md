---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili manajer yang memegang perilaku placeholder footer, tanggal-waktu, nomor halaman untuk semua jenis slide.
type: docs
url: /id/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Mewakili manajer yang memegang perilaku placeholder footer, tanggal-waktu, nomor halaman untuk semua jenis slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder footer ada. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder nomor halaman ada. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder tanggal-waktu ada. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Mengubah visibilitas placeholder footer slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Mengubah visibilitas placeholder nomor halaman slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Mengubah visibilitas placeholder tanggal-waktu slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Menetapkan teks ke placeholder footer slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Menetapkan teks ke placeholder tanggal-waktu slide. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Mendapatkan nilai yang menunjukkan bahwa placeholder footer ada. Baca boolean.

**Mengembalikan:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Mendapatkan nilai yang menunjukkan bahwa placeholder nomor halaman ada. Baca boolean.

**Mengembalikan:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Mendapatkan nilai yang menunjukkan bahwa placeholder tanggal-waktu ada. Baca boolean.

**Mengembalikan:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder footer slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder footer terlihat, jika tidak - menyembunyikannya. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder nomor halaman slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, jika tidak - menyembunyikannya. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder tanggal-waktu slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, jika tidak - menyembunyikannya. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Menetapkan teks ke placeholder footer slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Menetapkan teks ke placeholder tanggal-waktu slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan ditetapkan. |