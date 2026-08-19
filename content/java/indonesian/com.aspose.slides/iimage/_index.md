---
title: IImage
second_title: Referensi API Aspose.Slides untuk Java
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
| [save(String filename)](#save-java.lang.String-) | Menyimpan gambar ke sebuah file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Menyimpan gambar ke sebuah file dalam format yang ditentukan. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Menyimpan gambar ke stream dalam format yang ditentukan. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Menyimpan gambar ke sebuah file dalam format dan kualitas yang ditentukan. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Menyimpan gambar ke stream dalam format dan kualitas yang ditentukan. |
| [getSize()](#getSize--) | Mendapatkan ukuran gambar. |
| [getWidth()](#getWidth--) | Mendapatkan lebar gambar dalam piksel. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi gambar dalam piksel. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Menyimpan gambar ke sebuah file.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Menyimpan gambar ke sebuah file dalam format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |
| format | int | Format gambar. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Menyimpan gambar ke stream dalam format yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream tempat gambar akan disimpan. |
| format | int | Format gambar. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Menyimpan gambar ke sebuah file dalam format dan kualitas yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Path ke file tempat gambar akan disimpan. |
| format | int | Format gambar. |
| quality | int | Kualitas gambar yang disimpan (0 sampai 100). Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); untuk semua format lain, parameter ini diabaikan. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Menyimpan gambar ke stream dalam format dan kualitas yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream tempat gambar akan disimpan. |
| format | int | Format gambar. |
| quality | int | Kualitas gambar yang disimpan (0 sampai 100). Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); untuk semua format lain, diabaikan. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

Mendapatkan ukuran gambar.

**Mengembalikan:**
java.awt.Dimension
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