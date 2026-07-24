---
title: Convert
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu dönüştürmek için tasarlanmış bir grup yöntemi temsil eder.
type: docs
weight: 27
url: /tr/aspose.slides.lowcode/convert/
---
## Dönüştürme sınıfı

Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)'yi, gerekli dışa aktarma formatını belirlemek için verilen çıkış yolu uzantısını kullanarak dönüştürür. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | İç giriş sunumunu bir dizi JPEG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | İç giriş sunumunu bir dizi JPEG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | İç giriş sunumunu bir dizi JPEG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)'yi PDF'ye dönüştürür. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/)'yi PDF'ye dönüştürür. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)'yi PDF'ye dönüştürür. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/)'yi PDF'ye dönüştürür. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | İç giriş sunumunu bir dizi PNG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | İç giriş sunumunu bir dizi PNG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | İç giriş sunumunu bir dizi PNG formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)'yi SVG'ye dönüştürür. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/)'yi SVG'ye dönüştürür. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/)'yi SVG'ye dönüştürür. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/)'yi SVG'ye dönüştürür. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/)'yi SVG'ye dönüştürür. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | İç giriş sunumunu bir dizi TIFF formatı görüntüsüne dönüştürür.

 Eğer çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse, sonuç "myPath/myFilename_N.tiff" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | İç giriş sunumunu özel seçeneklerle TIFF formatına dönüştürür. Eğer çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse ve *multipage* **false** ise, sonuç "myPath/myFilename_N.tiff" dosyaları dizisi olarak kaydedilir, burada N bir slayt numarasıdır. Aksi takdirde, eğer *multipage* **true** ise, sonuç çok sayfalı bir "myPath/myFilename.tiff" belgesi olur. |

## Tip tanımı

| Tip tanımı | Açıklama |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Her [Slide](../../aspose.slides/slide/) için çağrılacak geri arama, geri döndürülecek çıkış yolu beklenir. |

## Açıklamalar



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## İlgili

* Ad alanı [Aspose::Slides::LowCode](../)
* Kütüphane [Aspose.Slides](../../)