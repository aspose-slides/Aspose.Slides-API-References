---
title: PPImage
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah gambar dalam presentasi.
type: docs
url: /id/com.aspose.slides/ppimage/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Mewakili sebuah gambar dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data gambar. |
| [getImage()](#getImage--) | Mengembalikan salinan gambar. |
| [getSvgImage()](#getSvgImage--) | Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Mengganti data gambar. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Mengganti data gambar. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Mengganti data gambar. |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME gambar, yang dienkode dalam BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Mengembalikan lebar gambar. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi gambar. |
| [getX()](#getX--) | Mengembalikan offset X gambar. |
| [getY()](#getY--) | Mengembalikan offset Y gambar. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash gambar. |
| [dispose()](#dispose--) | Membuang objek. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Mengembalikan salinan data gambar. Hanya baca  byte[] .

**Mengembalikan:**
byte[] - Array byte
### getImage() {#getImage--}
```
public final IImage getImage()
```


Mengembalikan salinan gambar. Hanya baca [IImage](../../com.aspose.slides/iimage).

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Nilai ini menunjukkan bahwa gambar ini dibuat dari SVG.

**Mengembalikan:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Nilai ini menunjukkan bahwa gambar ini dibuat dari SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Mengganti data gambar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImageData | byte[] | Data gambar baru. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Mengganti data gambar. Perhatian: ketika Image adalah metafile - akan dirasterkan. Gunakan ReplaceImage(byte[]) sebagai gantinya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Gambar baru. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Mengganti data gambar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage baru. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Mengembalikan tipe MIME gambar, yang dienkode dalam BinaryData (\#getBinaryData.getBinaryData). Hanya baca String.

**Mengembalikan:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mengembalikan lebar gambar. Hanya baca  int .

**Mengembalikan:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mengembalikan tinggi gambar. Hanya baca  int .

**Mengembalikan:**
int
### getX() {#getX--}
```
public final int getX()
```


Mengembalikan offset X gambar. Hanya baca  int .

**Mengembalikan:**
int
### getY() {#getY--}
```
public final int getY()
```


Mengembalikan offset Y gambar. Hanya baca  int .

**Mengembalikan:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash gambar.

**Mengembalikan:**
int - Kode hash.
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang objek.