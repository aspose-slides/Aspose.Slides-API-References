---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator sınıfı

HTML oluşturucu.

IHtmlGenerator türü aşağıdaki üyeleri içerir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`slide_image_size`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Slayt görüntüsü boyutunu döndürür.<br/>            Yalnızca okuma **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Slayt görüntüsü boyutunun belirtildiği birimi döndürür.<br/>            Yalnızca okuma [`SvgCoordinateUnit`](/slides/python-net/tr/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Slayt görüntüsü boyutunun belirtildiği birimin css kodunu döndürür.<br/>            Yalnızca okuma **str**. |
| [`previous_slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Daha önce işlenen slayın indeksini döndürür veya ilk slayt işleniyorsa -1 döndürür.<br/>            Yalnızca okuma **int**. |
| [`slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_index/) | Şu anda işlenen slayın indeksini döndürür.<br/>            Yalnızca okuma **int**. |
| [`next_slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Mevcut slayttan sonra işlenecek slayın indeksini döndürür veya şu anda son slayt işleniyorsa -1 döndürür.<br/>            Yalnızca okuma **int**. |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#str) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Biçimlendirilmiş HTML metni ekler. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıkları ile değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıkları ile değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıkları ile değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |


### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)