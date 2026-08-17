---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Sunumda bir görüntüyü temsil eder.
type: docs
url: /tr/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Sunumda bir görüntüyü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Bir görüntünün verilerinin kopyasını döndürür. |
| [getImage()](#getImage--) | Bir görüntünün kopyasını döndürür. |
| [getSvgImage()](#getSvgImage--) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Resim verilerini değiştirir. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Görüntüyü değiştirir. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Görüntüyü değiştirir. |
| [getContentType()](#getContentType--) | Bir görüntünün MIME türünü döndürür, \#getBinaryData.getBinaryData içinde kodlanmış. |
| [getWidth()](#getWidth--) | Bir görüntünün genişliğini döndürür. |
| [getHeight()](#getHeight--) | Bir görüntünün yüksekliğini döndürür. |
| [getX()](#getX--) | Bir görüntünün X ofsetini döndürür. |
| [getY()](#getY--) | Bir görüntünün Y ofsetini döndürür. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Bir görüntünün verilerinin kopyasını döndürür. Salt-okunur byte[].

**Döndürür:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Bir görüntünün kopyasını döndürür. Salt-okunur \#getImage.getImage.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu görüntünün SVG'den oluşturulduğunu gösterir.

**Döndürür:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu görüntünün SVG'den oluşturulduğunu gösterir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Resim verilerini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImageData | byte[] | Yeni görüntünün verisi. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Görüntüyü değiştirir. Dikkat: Image bir metafile olduğunda rasterleştirilecektir. Bunun yerine replaceImage(byte[]) kullanın

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Yeni görüntü. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Görüntüyü değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Yeni IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Bir görüntünün MIME türünü döndürür, \#getBinaryData.getBinaryData içinde kodlanmış. Salt-okunur String.

**Döndürür:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Bir görüntünün genişliğini döndürür. Salt-okunur int.

**Döndürür:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Bir görüntünün yüksekliğini döndürür. Salt-okunur int.

**Döndürür:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Bir görüntünün X ofsetini döndürür. Salt-okunur int.

**Döndürür:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Bir görüntünün Y ofsetini döndürür. Salt-okunur int.

**Döndürür:**
int