---
title: PPImage
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir sunumdaki görseli temsil eder.
type: docs
url: /tr/com.aspose.slides/ppimage/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Bir sunumda bulunan bir görseli temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Görselin verilerinin bir kopyasını döndürür. |
| [getImage()](#getImage--) | Görselin bir kopyasını döndürür. |
| [getSvgImage()](#getSvgImage--) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Görsel verisini değiştirir. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Görsel verisini değiştirir. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Görsel verisini değiştirir. |
| [getContentType()](#getContentType--) | Görselin MIME tipini döndürür, BinaryData içinde kodlanmış (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Görselin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Görselin yüksekliğini döndürür. |
| [getX()](#getX--) | Görselin X ofsetini döndürür. |
| [getY()](#getY--) | Görselin Y ofsetini döndürür. |
| [hashCode()](#hashCode--) | Görselin karma kodunu döndürür. |
| [dispose()](#dispose--) | Nesneyi yok eder. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Görselin verilerinin bir kopyasını döndürür. Salt okunur byte[] .

**Döndürür:**
byte[] - Bayt dizisi
### getImage() {#getImage--}
```
public final IImage getImage()
```


Görselin bir kopyasını döndürür. Salt okunur [IImage](../../com.aspose.slides/iimage).

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu görselin SVG'den oluşturulduğunu gösterir.

**Döndürür:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu görselin SVG'den oluşturulduğunu gösterir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Görsel verisini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImageData | byte[] | Yeni görselin verisi. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Görsel verisini değiştirir. Dikkat: Görsel bir metafile olduğunda rasterleştirilecektir. Bunun yerine ReplaceImage(byte[]) kullanın

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Yeni görsel. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Görsel verisini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Yeni IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Görselin MIME tipini döndürür, BinaryData içinde kodlanmış (\#getBinaryData.getBinaryData). Salt okunur String.

**Döndürür:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Görselin genişliğini döndürür. Salt okunur int .

**Döndürür:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Görselin yüksekliğini döndürür. Salt okunur int .

**Döndürür:**
int
### getX() {#getX--}
```
public final int getX()
```


Görselin X ofsetini döndürür. Salt okunur int .

**Döndürür:**
int
### getY() {#getY--}
```
public final int getY()
```


Görselin Y ofsetini döndürür. Salt okunur int .

**Döndürür:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Görselin karma kodunu döndürür.

**Döndürür:**
int - Karma kodu.
### dispose() {#dispose--}
```
public final void dispose()
```


Nesneyi yok eder.