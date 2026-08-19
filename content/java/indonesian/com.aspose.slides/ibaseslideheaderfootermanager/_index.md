---
title: IBaseSlideHeaderFooterManager
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili manajer yang menyimpan perilaku placeholder footer, tanggal-waktu, dan nomor halaman untuk semua jenis slide.
type: docs
url: /id/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Mewakili pengelola yang memegang perilaku placeholder footer, tanggal-waktu, nomor halaman untuk semua jenis slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder footer ada. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder nomor halaman ada. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Mendapatkan nilai yang menunjukkan bahwa placeholder tanggal-waktu ada. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Mengubah visibilitas placeholder footer slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Mengubah visibilitas placeholder nomor halaman slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Mengubah visibilitas placeholder tanggal-waktu slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Mengatur teks pada placeholder footer slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Mengatur teks pada placeholder tanggal-waktu slide. |
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
| isVisible | boolean | true - membuat placeholder footer terlihat, lainnya - menyembunyikannya. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder nomor halaman slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder nomor halaman terlihat, lainnya - menyembunyikannya. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Mengubah visibilitas placeholder tanggal-waktu slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isVisible | boolean | true - membuat placeholder tanggal-waktu terlihat, lainnya - menyembunyikannya. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Mengatur teks pada placeholder footer slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Mengatur teks pada placeholder tanggal-waktu slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan diatur. |