---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /id/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Mewakili gambar dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Mengembalikan salinan data gambar. |
| [getImage()](#getImage--) | Mengembalikan salinan gambar. |
| [getSvgImage()](#getSvgImage--) | Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Mengganti data gambar. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Mengganti gambar. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Mengganti gambar. |
| [getContentType()](#getContentType--) | Mengembalikan tipe MIME sebuah gambar, yang dienkode dalam \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Mengembalikan lebar sebuah gambar. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi sebuah gambar. |
| [getX()](#getX--) | Mengembalikan offset X sebuah gambar. |
| [getY()](#getY--) | Mengembalikan offset Y sebuah gambar. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan salinan data gambar. Hanya-baca byte[].

**Mengembalikan:**  
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Mengembalikan salinan gambar. Hanya-baca \#getImage.getImage.

**Mengembalikan:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Mengembalikan atau mengatur objek ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Nilai ini menunjukkan bahwa gambar ini dibuat dari SVG.

**Mengembalikan:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
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
public abstract void replaceImage(byte[] newImageData)
```


Mengganti data gambar.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImageData | byte[] | Data gambar baru. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Mengganti gambar. Perhatian: ketika Image adalah metafile - akan dirasterkan. Gunakan replaceImage(byte[]) sebagai gantinya

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Gambar baru. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Mengganti gambar.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage baru. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Mengembalikan tipe MIME sebuah gambar, yang dienkode dalam \#getBinaryData.getBinaryData. Hanya-baca String.

**Mengembalikan:**  
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Mengembalikan lebar sebuah gambar. Hanya-baca int.

**Mengembalikan:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Mengembalikan tinggi sebuah gambar. Hanya-baca int.

**Mengembalikan:**  
int
### getX() {#getX--}
```
public abstract int getX()
```


Mengembalikan offset X sebuah gambar. Hanya-baca int.

**Mengembalikan:**  
int
### getY() {#getY--}
```
public abstract int getY()
```


Mengembalikan offset Y sebuah gambar. Hanya-baca int.

**Mengembalikan:**  
int