---
title: HtmlGenerator class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator sınıfı

HTML oluşturucu.

HtmlGenerator türü aşağıdaki üyelere sahiptir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`slide_image_size`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/slide_image_size/) | Returns slide image size.<br/>            Yalnızca okunabilir **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            Yalnızca okunabilir [`SvgCoordinateUnit`](/slides/python-net/tr/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            Yalnızca okunabilir **str**. |
| [`previous_slide_index`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            Yalnızca okunabilir **int**. |
| [`slide_index`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            Yalnızca okunabilir **int**. |
| [`next_slide_index`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            Yalnızca okunabilir **int**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_html/#str) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_html/#listchar) | Biçimlendirilmiş HTML metni ekler. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Biçimlendirilmiş HTML metni ekler. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_text/#str) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_text(self, text)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_text/#listchar) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir.<br/>            Satır sonları ve boşluklar değiştirilmez. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/tr/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Özellik değerini tırnak içine alır ve HTML dosyasına ekler. |

### Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)