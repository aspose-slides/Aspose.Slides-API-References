---
title: IHtmlGenerator class
second_title: Aspose.Slides a Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator osztály

HTML generátor.

Az IHtmlGenerator típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Visszaadja a dia kép méretét.<br/>            Csak olvasható [`SizeF`](/slides/python-net/hu/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Visszaadja azt a mértékegységet, amelyben a dia kép mérete van megadva.<br/>            Csak olvasható [`SvgCoordinateUnit`](/slides/python-net/hu/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Visszaadja a mértékegység CSS kódját, amelyben a dia kép mérete van megadva.<br/>            Csak olvasható **str**. |
| [`previous_slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Visszaadja az előzőleg renderelt dia indexét, vagy -1-et, ha az első dia renderelés alatt van.<br/>            Csak olvasható **int**. |
| [`slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/slide_index/) | Visszaadja a jelenleg renderelt dia indexét.<br/>            Csak olvasható **int**. |
| [`next_slide_index`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Visszaadja annak a diáknak az indexét, amely a jelenlegi dia után lesz renderelve, vagy -1-et, ha éppen az utolsó dia renderelése folyik.<br/>            Csak olvasható **int**. |

## Metódusok

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#str) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Formázott HTML szöveget ad hozzá. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#str) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hu/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Az attribútum értékét idézőjelek közé teszi, és hozzáadja a html fájlhoz. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)