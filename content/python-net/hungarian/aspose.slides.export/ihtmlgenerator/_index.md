---
title: IHtmlGenerator class
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator osztály

HTML generátor.

Az IHtmlGenerator típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Visszaadja a diakép méretét.<br/>            Csak olvasható **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Visszaadja az egységet, amelyben a diakép mérete meg van adva.<br/>            Csak olvasható [`SvgCoordinateUnit`](/slides/python-net/hu/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Visszaadja az egység CSS kódját, amelyben a diakép mérete meg van adva.<br/>            Csak olvasható **str**. |
| [`previous_slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Visszaadja az előzőleg renderelt dia indexét, vagy -1-et, ha az első dia renderelés alatt áll.<br/>            Csak olvasható **int**. |
| [`slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_index/) | Visszaadja a jelenleg renderelt dia indexét.<br/>            Csak olvasható **int**. |
| [`next_slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Visszaadja annak a diának az indexét, amely a jelenlegi dia után lesz renderelve, vagy -1-et, ha a jelenlegi dia az utolsó.<br/>            Csak olvasható **int**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#str) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Formázott HTML szöveget ad hozzá. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#str) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokra cserélve.<br/>            A sortöréseket és szóközöket nem cseréli. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokra cserélve.<br/>            A sortöréseket és szóközöket nem cseréli. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokra cserélve.<br/>            A sortöréseket és szóközöket nem cseréli. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)