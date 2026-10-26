---
title: PPImage
second_title: Aspose.Slides için Java API Referansı
description: Bir sunumda bir görüntüyü temsil eder.
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

Sunumda bir görüntüyü temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Bir görüntünün verisinin kopyasını döndürür. |
| [getImage()](#getImage--) | Bir görüntünün kopyasını döndürür. |
| [getSvgImage()](#getSvgImage--) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Görüntü verisini değiştirir. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Görüntü verisini değiştirir. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Görüntü verisini değiştirir. |
| [getContentType()](#getContentType--) | Bir görüntünün MIME tipini döndürür, BinaryData içinde kodlanmış (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Bir görüntünün genişliğini döndürür. |
| [getHeight()](#getHeight--) | Bir görüntünün yüksekliğini döndürür. |
| [getX()](#getX--) | Bir görüntünün X ötelemesini döndürür. |
| [getY()](#getY--) | Bir görüntünün Y ötelemesini döndürür. |
| [hashCode()](#hashCode--) | Bir görüntünün hash kodunu döndürür. |
| [dispose()](#dispose--) | Nesneyi yok eder. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Bir görüntünün verisinin kopyasını döndürür. Salt okunur  byte[] .

**Döndürür:**
byte[] - Bayt dizisi
### getImage() {#getImage--}
```
public final IImage getImage()
```


Bir görüntünün kopyasını döndürür. Salt okunur [IImage](../../com.aspose.slides/iimage).

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


ISvgImage nesnesini döndürür veya ayarlar [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Bu değer, bu görüntünün SVG'den oluşturulduğunu gösterir.

**Döndürür:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
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
public final void replaceImage(byte[] newImageData)
```


Görüntü verisini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImageData | byte[] | Yeni görüntünün verisi. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Görüntü verisini değiştirir. Dikkat: Image bir metafile ise rasterleştirilecektir. Bunun yerine ReplaceImage(byte[]) kullanın

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Yeni görüntü. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Görüntü verisini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Yeni IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Bir görüntünün MIME tipini döndürür, BinaryData içinde kodlanmış (\#getBinaryData.getBinaryData). Salt okunur String.

**Döndürür:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bir görüntünün genişliğini döndürür. Salt okunur  int .

**Döndürür:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Bir görüntünün yüksekliğini döndürür. Salt okunur  int .

**Döndürür:**
int
### getX() {#getX--}
```
public final int getX()
```


Bir görüntünün X ötelemesini döndürür. Salt okunur  int .

**Döndürür:**
int
### getY() {#getY--}
```
public final int getY()
```


Bir görüntünün Y ötelemesini döndürür. Salt okunur  int .

**Döndürür:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bir görüntünün hash kodunu döndürür.

**Döndürür:**
int - Hash kodu.
### dispose() {#dispose--}
```
public final void dispose()
```


Nesneyi yok eder.