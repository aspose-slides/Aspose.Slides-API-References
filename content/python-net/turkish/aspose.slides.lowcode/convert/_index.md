---
title: Convert class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/convert/
---
## Convert sınıf

Bir [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) dönüştürmeyi amaçlayan bir dizi yöntemi temsil eder.

Convert türü aşağıdaki üyeleri sunar:

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`to_pdf(pres_path, out_path)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_pdf/#str-str) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| [`to_pdf(pres_path, out_path, options)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_pdf/#str-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| [`to_pdf(pres, out_path)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_pdf/#presentation-str) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| [`to_pdf(pres, out_path, options)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_pdf/#presentation-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı PDF'ye dönüştürür. |
| [`to_svg(pres_path)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_svg/#str) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı SVG'ye dönüştürür. |
| [`to_svg(pres, options)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_svg/#presentation-asposeslidesexportisvgoptions) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'i SVG'ye dönüştürür. |
| [`to_jpeg(pres, output_file_name)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_jpeg/#presentation-str) | Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.jpeg" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir. |
| [`to_jpeg(pres, output_file_name, image_size)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-asposepydrawingsize) | Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.jpeg" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir. |
| [`to_jpeg(pres, output_file_name, scale, options)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-float-asposeslidesexportirenderingoptions) | Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.jpeg" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir. |
| [`to_png(pres, output_file_name)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_png/#presentation-str) | Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.png" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.png" dosyaları olarak kaydedilir. |
| [`to_png(pres, output_file_name, image_size)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_png/#presentation-str-asposepydrawingsize) | Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.png" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.png" dosyaları olarak kaydedilir. |
| [`to_png(pres, output_file_name, scale, options)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_png/#presentation-str-float-asposeslidesexportirenderingoptions) | Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.png" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.png" dosyaları olarak kaydedilir. |
| [`to_tiff(pres, output_file_name)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_tiff/#presentation-str) | Giriş sunumunu TIFF formatında bir dizi görüntüye dönüştürür.  <br/>            Eğer çıkış dosya adı "myPath/myFilename.tiff" olarak verilirse, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.tiff" dosyaları olarak kaydedilir. |
| [`to_tiff(pres, output_file_name, options, multipage)`](/slides/python-net/tr/aspose.slides.lowcode/convert/to_tiff/#presentation-str-asposeslidesexportitiffoptions-bool) | Giriş sunumunu özel seçeneklerle TIFF formatına dönüştürür.<br/>            Eğer çıkış dosya adı "myPath/myFilename.tiff" olarak verilirse ve `multipage` `false` ise, <br/>            sonuç, N slayt numarası olan "myPath/myFilename_N.tiff" dosyaları olarak kaydedilir.<br/>            Aksi takdirde, `multipage` `true` ise, sonuç çok sayfalı "myPath/myFilename.tiff" belgesi olur. |
| [`auto_by_extension(pres_path, out_path)`](/slides/python-net/tr/aspose.slides.lowcode/convert/auto_by_extension/#str-str) | Gereken dışa aktarma biçimini belirlemek için verilen çıkış yolu uzantısını kullanarak [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı dönüştürür. |

### Ayrıca Bakınız
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)