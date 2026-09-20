---
title: IHtmlGenerator class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator třída

Html generátor.

Typ IHtmlGenerator exponuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`slide_image_size`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Vrací velikost obrázku snímku.<br/>            Pouze pro čtení **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Vrací jednotku, ve které je velikost obrázku snímku uvedena.<br/>            Pouze pro čtení [`SvgCoordinateUnit`](/slides/python-net/cs/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku uvedena.<br/>            Pouze pro čtení **str**. |
| [`previous_slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Vrací index předchozího vykresleného snímku nebo -1, pokud se vykresluje první snímek.<br/>            Pouze pro čtení **int**. |
| [`slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/slide_index/) | Vrací index aktuálně vykreslovaného snímku.<br/>            Pouze pro čtení **int**. |
| [`next_slide_index`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud se právě vykresluje poslední snímek.<br/>            Pouze pro čtení **int**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#str) | Přidá formátovaný HTML text. |
| [`add_html(self, html)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Přidá formátovaný HTML text. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Přidá formátovaný HTML text. |
| [`add_text(self, text)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#str) | Přidá prostý text do HTML souborů, nahrazuje speciální znaky HTML entity.<br/>            Zalomení řádků a mezery nejsou nahrazeny. |
| [`add_text(self, text)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Přidá prostý text do HTML souborů, nahrazuje speciální znaky HTML entity.<br/>            Zalomení řádků a mezery nejsou nahrazeny. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Přidá prostý text do HTML souborů, nahrazuje speciální znaky HTML entity.<br/>            Zalomení řádků a mezery nejsou nahrazeny. |
| [`add_attribute_value(self, value)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Uvozovky kolem hodnoty atributu a přidá ji do HTML souboru. |
| [`add_attribute_value(self, value)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Uvozovky kolem hodnoty atributu a přidá ji do HTML souboru. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/cs/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Uvozovky kolem hodnoty atributu a přidá ji do HTML souboru. |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)