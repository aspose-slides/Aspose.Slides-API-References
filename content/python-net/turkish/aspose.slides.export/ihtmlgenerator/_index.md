---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator sınıf

HTML oluşturucu.

IHtmlGenerator türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`slide_image_size`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Slayt görüntüsü boyutunu döndürür.<br/>            Salt-okunur [`SizeF`](/slides/python-net/tr/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Slayt görüntüsü boyutunun belirtildiği bir birimi döndürür.<br/>            Salt-okunur [`SvgCoordinateUnit`](/slides/python-net/tr/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Slayt görüntüsü boyutunun belirtildiği bir birimin css kodunu döndürür.<br/>            Salt-okunur **str**. |
| [`previous_slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Daha önce oluşturulmuş slayın dizinini döndürür veya ilk slayt oluşturuluyorsa -1 döndürür.<br/>            Salt-okunur **int**. |
| [`slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/slide_index/) | Şu anda oluşturulan slayın dizinini döndürür.<br/>            Salt-okunur **int**. |
| [`next_slide_index`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Geçerli slayttan sonra oluşturulacak slayın dizinini döndürür veya son slaytı oluşturuyorsa -1 döndürür.<br/>            Salt-okunur **int**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#str) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Biçimlendirilmiş HTML metni ekler. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluk karakterleri değiştirilmez. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluk karakterleri değiştirilmez. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluk karakterleri değiştirilmez. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/tr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |

### See Also
* module [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)