---
title: SlideImageFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: Sunumun HTML dışa aktarımı için slayt görüntüsünün kaydedileceği formatı belirler.
type: docs
url: /tr/com.aspose.slides/slideimageformat/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Sunumun HTML dışa aktarımı için slayt görüntüsü hangi formatta kaydedileceğini belirler.
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Yöntemler

| Method | Description |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slaytlar SVG formatına dönüştürülmelidir. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slaytlar raster görüntüye dönüştürülmelidir. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Slaytlar SVG formatına dönüştürülmelidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG dışa aktarma seçenekleri. |

**Döndürür:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) nesnesi.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Slaytlar raster görüntüye dönüştürülmelidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scale | float | Çıktı görüntüsünü ölçeklendirecek faktör. |
| imageFormat | int | Sonuç görüntünün formatı (ör. PNG, JPEG). |

**Döndürür:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -