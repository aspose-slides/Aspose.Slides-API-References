---
title: SlideImageFormat
second_title: Aspose.Slides for Java API Referansı
description: Sunumun HTML dışa aktarımı için slayt resminin kaydedileceği formatı belirler.
type: docs
url: /tr/com.aspose.slides/slideimageformat/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Sunumun HTML dışa aktarımı için slayt resminin kaydedileceği formatı belirler.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slaytların SVG formatına dönüştürülmesi gerekir. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slaytların raster (piksel tabanlı) bir görüntüye dönüştürülmesi gerekir. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Slaytlar bir SVG formatına dönüştürülmelidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG dışa aktarımı için seçenekler. |

**Dönüş Değeri:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) nesnesi.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Slaytlar bir raster (piksel tabanlı) görüntüye dönüştürülmelidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scale | float | Çıktı görüntüsünün ölçeklendirilme faktörü. |
| imageFormat | int | Oluşturulan görüntünün formatı (örn., PNG, JPEG). |

**Dönüş Değeri:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -