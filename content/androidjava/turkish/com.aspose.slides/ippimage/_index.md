---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Bir sunumda bir resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Bir sunumda bir resmi temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an image's data. |
| [getImage()](#getImage--) | Returns the copy of an image. |
| [getSvgImage()](#getSvgImage--) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Replaces image data. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Replaces image. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Replaces image. |
| [getContentType()](#getContentType--) | Returns a MIME type of an image, encoded in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Returns a width of an image. |
| [getHeight()](#getHeight--) | Returns a height of an image. |
| [getX()](#getX--) | Returns a X-offset of an image. |
| [getY()](#getY--) | Returns a Y-offset of an image. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Bir resmin verisinin bir kopyasını döndürür. Salt okunur byte[].

**Döndürür:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Bir resmin bir kopyasını döndürür. Salt okunur \#getImage.getImage.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu resmin SVG'den oluşturulduğunu gösterir.

**Döndürür:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu resmin SVG'den oluşturulduğunu gösterir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Resim verisini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImageData | byte[] | Yeni resmin verisi. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Resmi değiştirir. Dikkat: Image bir metafile olduğunda - rasterleştirilecektir. Bunun yerine replaceImage(byte[]) metodunu kullanın

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Yeni resim. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Resmi değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Yeni IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Bir resmin MIME türünü, \#getBinaryData.getBinaryData içinde kodlanmış olarak döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Bir resmin genişliğini döndürür. Salt okunur int.

**Döndürür:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Bir resmin yüksekliğini döndürür. Salt okunur int.

**Döndürür:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Bir resmin X ofsetini döndürür. Salt okunur int.

**Döndürür:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Bir resmin Y ofsetini döndürür. Salt okunur int.

**Döndürür:**
int