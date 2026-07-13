---
title: ImageCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi PPImage.
type: docs
url: /id/com.aspose.slides/imagecollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Mewakili koleksi PPImage.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah gambar dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Menambahkan salinan gambar dari presentasi lain. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Menambahkan gambar ke presentasi. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Menambahkan gambar ke presentasi dari aliran. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Membuat dan menambahkan gambar ke presentasi dari aliran. |
| [addImage(byte[] buffer)](#addImage-byte---) | Menambahkan gambar ke presentasi dari buffer yang ditentukan. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Menambahkan gambar ke presentasi dari objek Svg. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengulangi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan root sinkronisasi. |
### size() {#size--}
```
public final int size()
```


Mengembalikan jumlah gambar dalam koleksi. Baca-saja  int .

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [IPPImage](../../com.aspose.slides/ippimage).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Menambahkan salinan gambar dari presentasi lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Gambar sumber. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Menambahkan gambar ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Gambar yang akan ditambahkan.

--------------------

Metode ini mengonversi metafile WMF/EMF menjadi gambar PNG raster sebelum dimasukkan ke presentasi. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Menambahkan gambar ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan gambar.

--------------------

Metode ini dapat menambahkan metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Membuat dan menambahkan gambar ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan gambar file dari. |
| loadingStreamBehavior | int | Perilaku yang akan diterapkan pada aliran. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - [IPPImage](../../com.aspose.slides/ippimage) yang ditambahkan.
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Menambahkan gambar ke presentasi dari buffer yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Menambahkan gambar ke presentasi dari objek Svg.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objek gambar Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Mengembalikan enumerator yang mengulangi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengulangi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Sebuah java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks awal dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Baca-saja  boolean .

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan root sinkronisasi. Baca-saja  Object .

**Mengembalikan:**
java.lang.Object