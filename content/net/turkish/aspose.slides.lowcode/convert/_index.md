---
title: Convert
second_title: Aspose.Sildes için .NET API Referansı
description: Presentation../aspose.slides/presentation'ı dönüştürmek için tasarlanmış bir grup yöntemi temsil eder.
type: docs
weight: 7880
url: /tr/aspose.slides.lowcode/convert/
---
## Convert sınıfı

[`Presentation`](../../aspose.slides/presentation)'yi dönüştürmek için tasarlanmış bir grup yöntemi temsil eder.

```csharp
public static class Convert
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | [`Presentation`](../../aspose.slides/presentation)'yi, verilen çıktı yolu uzantısını kullanarak gerekli dışa aktarma biçimini belirlemek için dönüştürür. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Giriş sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verildiğinde, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Giriş sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verildiğinde, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Giriş sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verildiğinde, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | [`Presentation`](../../aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | [`Presentation`](../../aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Giriş sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verildiğinde, sonuç "myPath/myFilename_N.png" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Giriş sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verildiğinde, sonuç "myPath/myFilename_N.png" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Giriş sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verildiğinde, sonuç "myPath/myFilename_N.png" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | [`Presentation`](../../aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Giriş sunumunu bir dizi TIFF formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verildiğinde, sonuç "myPath/myFilename_N.tiff" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Giriş sunumunu özel seçeneklerle TIFF formatına dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verildiğinde ve *multipage* `false` ise, sonuç "myPath/myFilename_N.tiff" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır. *multipage* `true` ise, sonuç çok sayfalı "myPath/myFilename.tiff" belgesi olur. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Her [`Slide`](../../aspose.slides/slide) için çağrılacak geri çağrı, döndürülmesi beklenen çıktı yolu. |

### Örnekler

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Diğer

* ad alanı [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->