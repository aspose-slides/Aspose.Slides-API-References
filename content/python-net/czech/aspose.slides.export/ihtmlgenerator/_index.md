---
title: IHtmlGenerator class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ihtmlgenerator/
---
## třída IHtmlGenerator

Generátor HTML.

Typ IHtmlGenerator vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`slide_image_size`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Vrací velikost obrázku snímku.<br/>            Pouze pro čtení [`SizeF`](/slides/python-net/cs/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Vrací jednotku, ve které je specifikována velikost obrázku snímku.<br/>            Pouze pro čtení [`SvgCoordinateUnit`](/slides/python-net/cs/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku specifikována.<br/>            Pouze pro čtení **str**. |
| [`previous_slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Vrací index dříve vykresleného snímku nebo -1, pokud se vykresluje první snímek.<br/>            Pouze pro čtení **int**. |
| [`slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_index/) | Vrací index aktuálně vykreslovaného snímku.<br/>            Pouze pro čtení **int**. |
| [`next_slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je právě vykreslován poslední snímek.<br/>            Pouze pro čtení **int**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#str) | Přidá formátovaný text HTML. |
| [`add_html(self, html)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Přidá formátovaný text HTML. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Přidá formátovaný text HTML. |
| [`add_text(self, text)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#str) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entity.<br/>            Zlomky řádků a mezery nejsou nahrazeny. |
| [`add_text(self, text)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entity.<br/>            Zlomky řádků a mezery nejsou nahrazeny. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entity.<br/>            Zlomky řádků a mezery nejsou nahrazeny. |
| [`add_attribute_value(self, value)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Uzavře hodnotu atributu do uvozovek a přidá ji do souboru HTML. |
| [`add_attribute_value(self, value)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Uzavře hodnotu atributu do uvozovek a přidá ji do souboru HTML. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Uzavře hodnotu atributu do uvozovek a přidá ji do souboru HTML. |


### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)