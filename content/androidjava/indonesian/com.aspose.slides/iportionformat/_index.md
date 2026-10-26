---
title: IPortionFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas ini berisi properti pemformatan bagian teks.
type: docs
url: /id/com.aspose.slides/iportionformat/
---
**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), semua properti kelas ini dapat ditulis.

--------------------

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga untuk sebagian besar kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter pemformatan efektif termasuk yang diwarisi, Anda perlu menggunakan metode [getEffective](../../com.aspose.slides/iportionformat\#getEffective) yang mengembalikan sebuah instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Mengembalikan atau mengatur pengidentifikasi bookmark. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Mengembalikan atau mengatur pengidentifikasi bookmark. |
| [getSmartTagClean()](#getSmartTagClean--) | Menentukan apakah smart tag harus dibersihkan. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Menentukan apakah smart tag harus dibersihkan. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan bagian yang efektif dengan pewarisan yang diterapkan. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Mengembalikan atau mengatur pengidentifikasi bookmark. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Mengembalikan atau mengatur pengidentifikasi bookmark. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Menentukan apakah smart tag harus dibersihkan. Tidak ada pewarisan yang diterapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Menentukan apakah smart tag harus dibersihkan. Tidak ada pewarisan yang diterapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan bagian yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).