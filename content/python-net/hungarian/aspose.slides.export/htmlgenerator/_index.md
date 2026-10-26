---
title: HtmlGenerator class
second_title: Aspose.Slides Pythonhoz a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator osztály

HTML generátor.

A HtmlGenerator típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size/) | Visszaadja a dia kép méretét.<br/>            Csak olvasható [`SizeF`](/slides/python-net/hu/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Visszaadja az egységet, amelyben a dia kép mérete van megadva.<br/>            Csak olvasható [`SvgCoordinateUnit`](/slides/python-net/hu/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Visszaadja az egység CSS kódját, amelyben a dia kép mérete van megadva.<br/>            Csak olvasható **str**. |
| [`previous_slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/previous_slide_index/) | Visszaadja az előzőleg renderelt dia indexét, vagy -1, ha az első diát rendereli.<br/>            Csak olvasható **int**. |
| [`slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_index/) | Visszaadja a jelenleg renderelt dia indexét.<br/>            Csak olvasható **int**. |
| [`next_slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/next_slide_index/) | Visszaadja annak a diának az indexét, amely a jelenlegi dia után lesz renderelve, vagy -1, ha az utolsó diát rendereli jelenleg.<br/>            Csak olvasható **int**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#str) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#listchar) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Formázott HTML szöveget ad hozzá. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#str) | Általános szöveget ad a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortörések és szóközök nem kerülnek helyettesítésre. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#listchar) | Általános szöveget ad a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortörések és szóközök nem kerülnek helyettesítésre. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Általános szöveget ad a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortörések és szóközök nem kerülnek helyettesítésre. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Idézőjelekkel veszi körül az attribútum értékét, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Idézőjelekkel veszi körül az attribútum értékét, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Idézőjelekkel veszi körül az attribútum értékét, és hozzáadja a html fájlhoz. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)