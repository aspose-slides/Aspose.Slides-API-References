---
title: IHtmlGenerator class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator klass

HTML-generator.

Typen IHtmlGenerator exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`slide_image_size`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Returnerar storlek på bildspelsbilden.<br/>            Skrivskyddad **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Returnerar en enhet i vilken bildspelsbildens storlek anges.<br/>            Skrivskyddad [`SvgCoordinateUnit`](/slides/python-net/sv/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Returnerar en CSS-kod för enheten som bildspelsbildens storlek anges i.<br/>            Skrivskyddad **str**. |
| [`previous_slide_index`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Returnerar index för föregående renderade bild eller -1 om den första bilden renderas.<br/>            Skrivskyddad **int**. |
| [`slide_index`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/slide_index/) | Returnerar index för bilden som för närvarande renderas.<br/>            Skrivskyddad **int**. |
| [`next_slide_index`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Returnerar index för en bild som kommer att renderas efter den aktuella bilden eller -1 om den sista bilden för närvarande renderas.<br/>            Skrivskyddad **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_html/#str) | Lägger till formaterad HTML-text. |
| [`add_html(self, html)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Lägger till formaterad HTML-text. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Lägger till formaterad HTML-text. |
| [`add_text(self, text)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_text/#str) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter.<br/>            Radbrytningar och blanksteg ersätts inte. |
| [`add_text(self, text)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter.<br/>            Radbrytningar och blanksteg ersätts inte. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter.<br/>            Radbrytningar och blanksteg ersätts inte. |
| [`add_attribute_value(self, value)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Citerar attributvärde och lägger till det i HTML-filen. |
| [`add_attribute_value(self, value)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Citerar attributvärde och lägger till det i HTML-filen. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/sv/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Citerar attributvärde och lägger till det i HTML-filen. |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)