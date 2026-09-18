---
title: HtmlGenerator class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator osztály

Html generátor.

A HtmlGenerator típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size/) | Visszaadja a dia kép méretét.<br/>            Csak olvasható **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Visszaadja azt a mértékegységet, amelyben a dia kép mérete meg van adva.<br/>            Csak olvasható [`SvgCoordinateUnit`](/slides/python-net/hu/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Visszaadja a mértékegység CSS kódját, amelyben a dia kép mérete meg van adva.<br/>            Csak olvasható **str**. |
| [`previous_slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/previous_slide_index/) | Visszaadja az előzőleg renderelt dia indexét, vagy -1-et, ha az első dia kerül renderelésre.<br/>            Csak olvasható **int**. |
| [`slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/slide_index/) | Visszaadja a jelenleg renderelt dia indexét.<br/>            Csak olvasható **int**. |
| [`next_slide_index`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/next_slide_index/) | Visszaadja a dia indexét, amely a jelenlegi dia után lesz renderelve, vagy -1-et, ha a jelenleg renderelt dia az utolsó.<br/>            Csak olvasható **int**. |

## Metódusok

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#str) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#listchar) | Formázott HTML szöveget ad hozzá. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Formázott HTML szöveget ad hozzá. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#str) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_text(self, text)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#listchar) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Egyszerű szöveget ad hozzá a html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve.<br/>            A sortöréseket és szóközöket nem helyettesíti. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Az attribútum értékét idézőjelekbe teszi és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Az attribútum értékét idézőjelekbe teszi és hozzáadja a html fájlhoz. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/hu/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Az attribútum értékét idézőjelekbe teszi és hozzáadja a html fájlhoz. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)