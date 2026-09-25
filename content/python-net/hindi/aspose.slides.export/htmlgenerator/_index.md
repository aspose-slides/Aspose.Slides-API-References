---
title: HtmlGenerator class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator वर्ग

Html generator.

HtmlGenerator प्रकार निम्न सदस्य प्रदर्शित करता है:

## गुण

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/slide_image_size/) | Returns slide image size.<br/>            केवल-पढ़ने योग्य [`SizeF`](/slides/python-net/hi/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            केवल-पढ़ने योग्य [`SvgCoordinateUnit`](/slides/python-net/hi/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            केवल-पढ़ने योग्य **str**. |
| [`previous_slide_index`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            केवल-पढ़ने योग्य **int**. |
| [`slide_index`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            केवल-पढ़ने योग्य **int**. |
| [`next_slide_index`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            केवल-पढ़ने योग्य **int**. |

## विधियाँ

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_html/#str) | Adds formatted HTML text. |
| [`add_html(self, html)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_html/#listchar) | Adds formatted HTML text. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Adds formatted HTML text. |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_text/#str) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_text/#listchar) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hi/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Quotes attribute value and adds it to the html file. |


### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)