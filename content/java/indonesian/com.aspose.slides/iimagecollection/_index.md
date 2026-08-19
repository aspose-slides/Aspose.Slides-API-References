---
title: IImageCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi PPImage.
type: docs
url: /id/com.aspose.slides/iimagecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Mewakili koleksi PPImage.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan gambar berdasarkan indeksnya. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Menambahkan gambar ke presentasi. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Menambahkan gambar ke presentasi dari aliran. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Membuat dan menambahkan gambar ke presentasi dari aliran. |
| [addImage(byte[] buffer)](#addImage-byte---) | Menambahkan gambar ke presentasi dari buffer yang ditentukan. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Menambahkan salinan gambar dari presentasi lain. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Menambahkan gambar ke presentasi dari objek SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Mengembalikan gambar berdasarkan indeksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Menambahkan gambar ke presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Gambar untuk ditambahkan.

--------------------

Metode ini mengonversi file metafile WMF/EMF menjadi gambar PNG raster sebelum disisipkan ke presentasi. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Menambahkan gambar ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan gambar dari.

--------------------

Metode ini dapat menambahkan file metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Membuat dan menambahkan gambar ke presentasi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan file gambar dari. |
| loadingStreamBehavior | int | Perilaku yang akan diterapkan pada aliran. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - [IPPImage](../../com.aspose.slides/ippimage) yang ditambahkan.
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Menambahkan gambar ke presentasi dari buffer yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Menambahkan salinan gambar dari presentasi lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Gambar sumber. |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Menambahkan gambar ke presentasi dari objek SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | objek SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.