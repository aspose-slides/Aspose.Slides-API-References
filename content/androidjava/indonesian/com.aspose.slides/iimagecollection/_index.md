---
title: IImageCollection
second_title: Referensi API Java Aspose.Slides untuk Android
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

| Method | Description |
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Menambahkan gambar ke presentasi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Gambar untuk ditambahkan.

--------------------

Metode ini mengonversi berkas metafile WMF/EMF menjadi gambar PNG raster sebelum dimasukkan ke presentasi. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Menambahkan gambar ke presentasi dari aliran.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan gambar.

--------------------

Metode ini dapat menambahkan berkas metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Membuat dan menambahkan gambar ke presentasi dari aliran.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk menambahkan file gambar. |
| loadingStreamBehavior | int | Perilaku yang akan diterapkan pada aliran. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Ditambahkan [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Menambahkan gambar ke presentasi dari buffer yang ditentukan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Menambahkan salinan gambar dari presentasi lain.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Gambar sumber. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Menambahkan gambar ke presentasi dari objek SVG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | objek gambar SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang ditambahkan.