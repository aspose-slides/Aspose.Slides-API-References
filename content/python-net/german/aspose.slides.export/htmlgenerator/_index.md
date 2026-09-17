---
title: HtmlGenerator class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator Klasse

HTML-Generator.

Der HtmlGenerator-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`slide_image_size`](/slides/python-net/de/aspose.slides.export/htmlgenerator/slide_image_size/) | Gibt die Größe des Folienbildes zurück.<br/>            Nur lesbar **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/de/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist.<br/>            Nur lesbar [`SvgCoordinateUnit`](/slides/python-net/de/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/de/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist.<br/>            Nur lesbar **str**. |
| [`previous_slide_index`](/slides/python-net/de/aspose.slides.export/htmlgenerator/previous_slide_index/) | Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird.<br/>            Nur lesbar **int**. |
| [`slide_index`](/slides/python-net/de/aspose.slides.export/htmlgenerator/slide_index/) | Gibt den Index der gerade gerenderten Folie zurück.<br/>            Nur lesbar **int**. |
| [`next_slide_index`](/slides/python-net/de/aspose.slides.export/htmlgenerator/next_slide_index/) | Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die aktuelle Folie die letzte ist.<br/>            Nur lesbar **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_html/#str) | Fügt formatierten HTML-Text hinzu. |
| [`add_html(self, html)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_html/#listchar) | Fügt formatierten HTML-Text hinzu. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Fügt formatierten HTML-Text hinzu. |
| [`add_text(self, text)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_text/#str) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten.<br/>            Zeilenumbrüche und Leerzeichen werden nicht ersetzt. |
| [`add_text(self, text)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_text/#listchar) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten.<br/>            Zeilenumbrüche und Leerzeichen werden nicht ersetzt. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten.<br/>            Zeilenumbrüche und Leerzeichen werden nicht ersetzt. |
| [`add_attribute_value(self, value)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [`add_attribute_value(self, value)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/de/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)