---
title: Convert
second_title: Aspose.Sildes için .NET API Referansı
description: Presentation../aspose.slides/presentation'ı dönüştürmek için tasarlanmış bir grup yöntemi temsil eder.
type: docs
weight: 7860
url: /tr/aspose.slides.lowcode/convert/
---
## Convert sınıfı

Belirli bir [`Presentation`](../../aspose.slides/presentation)'ı dönüştürmek için tasarlanmış bir grup yöntemi temsil eder.

```csharp
public static class Convert
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | [`Presentation`](../../aspose.slides/presentation)'ı, verilen çıktı yolu uzantısını kullanarak gerekli dışa aktarma biçimini belirlemek için dönüştürür. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Girdi sunumunu JPEG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Girdi sunumunu JPEG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Girdi sunumunu JPEG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | [`Presentation`](../../aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | [`Presentation`](../../aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Girdi sunumunu PNG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Girdi sunumunu PNG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Girdi sunumunu PNG biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | [`Presentation`](../../aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Girdi sunumunu TIFF biçimindeki bir dizi görsele dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse, sonuç "myPath/myFilename_N.tiff" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Girdi sunumunu özel seçeneklerle TIFF biçimine dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse ve *multipage* `false` ise, sonuç "myPath/myFilename_N.tiff" dosyaları biçiminde, N slayt numarası olmak üzere, kaydedilir. Aksi takdirde, *multipage* `true` ise, sonuç çok sayfalı "myPath/myFilename.tiff" belgesi olur. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Her [`Slide`](../../aspose.slides/slide) için çağrılacak geri arama, döndürülecek çıktı yolunu bekler. |

### Örnekler

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Ayrıca Bakınız

* ad alanı [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->