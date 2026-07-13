---
title: IImage
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili gambar raster atau vektor.
type: docs
url: /id/com.aspose.slides/iimage/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Mewakili gambar raster atau vektor.

--------------------

Antarmuka ini menyediakan abstraksi umum untuk menangani gambar raster dan vektor. Implementasi dapat bervariasi tergantung pada tipe gambar yang mendasarinya.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Menyimpan gambar ke file.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Menyimpan gambar ke file dalam format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |
| format | int | Format gambar. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Menyimpan gambar ke aliran dalam format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran tempat gambar akan disimpan. |
| format | int | Format gambar. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Menyimpan gambar ke file dalam format dan kualitas yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |
| format | int | Format gambar. |
| quality | int | Kualitas gambar yang disimpan (0 hingga 100). Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); untuk semua format lain, parameter diabaikan. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Menyimpan gambar ke aliran dalam format dan kualitas yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran tempat gambar akan disimpan. |
| format | int | Format gambar. |
| quality | int | Kualitas gambar yang disimpan (0 hingga 100). Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); untuk semua format lain, parameter diabaikan. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Mendapatkan ukuran gambar.

**Mengembalikan:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Mendapatkan lebar gambar dalam piksel.

**Mengembalikan:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Mendapatkan tinggi gambar dalam piksel.

**Mengembalikan:**
int