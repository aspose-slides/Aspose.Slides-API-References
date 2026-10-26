---
title: IPictureFillFormat class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat třída

Reprezentuje styl výplně obrázkem.

Typ IPictureFillFormat zveřejňuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/cs/aspose.slides/ipicturefillformat/dpi/) | Vrací nebo nastavuje DPI, který se používá k vyplnění obrázku.<br/>            Čtení/zápis **int**. |
| [`picture_fill_mode`](/slides/python-net/cs/aspose.slides/ipicturefillformat/picture_fill_mode/) | Vrací nebo nastavuje režim výplně obrázkem.<br/>            Čtení/zápis [`PictureFillMode`](/slides/python-net/cs/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/cs/aspose.slides/ipicturefillformat/picture/) | Vrací obrázek.<br/>            Pouze ke čtení [`ISlidesPicture`](/slides/python-net/cs/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/cs/aspose.slides/ipicturefillformat/crop_left/) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku.<br/>            Čtení/zápis **float**. |
| [`crop_top`](/slides/python-net/cs/aspose.slides/ipicturefillformat/crop_top/) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta z horní strany obrázku.<br/>            Čtení/zápis **float**. |
| [`crop_right`](/slides/python-net/cs/aspose.slides/ipicturefillformat/crop_right/) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku.<br/>            Čtení/zápis **float**. |
| [`crop_bottom`](/slides/python-net/cs/aspose.slides/ipicturefillformat/crop_bottom/) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta ze spodní strany obrázku.<br/>            Čtení/zápis **float**. |
| [`stretch_offset_left`](/slides/python-net/cs/aspose.slides/ipicturefillformat/stretch_offset_left/) | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním offsetem od levého okraje ohraničujícího rámečku tvaru.<br/>            Kladné procento určuje vnitřní odsazení, zatímco záporné procento určuje vnější odsazení.<br/>            Čtení/zápis **float**. |
| [`stretch_offset_top`](/slides/python-net/cs/aspose.slides/ipicturefillformat/stretch_offset_top/) | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním offsetem od horního okraje ohraničujícího rámečku tvaru.<br/>            Kladné procento určuje vnitřní odsazení, zatímco záporné procento určuje vnější odsazení.<br/>            Čtení/zápis **float**. |
| [`stretch_offset_right`](/slides/python-net/cs/aspose.slides/ipicturefillformat/stretch_offset_right/) | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním offsetem od pravého okraje ohraničujícího rámečku tvaru.<br/>            Kladné procento určuje vnitřní odsazení, zatímco záporné procento určuje vnější odsazení.<br/>            Čtení/zápis **float**. |
| [`stretch_offset_bottom`](/slides/python-net/cs/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním offsetem od spodního okraje ohraničujícího rámečku tvaru.<br/>            Kladné procento určuje vnitřní odsazení, zatímco záporné procento určuje vnější odsazení.<br/>            Čtení/zápis **float**. |
| [`tile_offset_x`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_offset_x/) | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech.<br/>            Kladná hodnota posune texturu doprava, záporná hodnota ji posune doleva.<br/>            Čtení/zápis **float**. |
| [`tile_offset_y`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_offset_y/) | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech.<br/>            Kladná hodnota posune texturu dolů, záporná hodnota ji posune nahoru.<br/>            Čtení/zápis **float**. |
| [`tile_scale_x`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_scale_x/) | Vrací nebo nastavuje vodorovné měřítko výplně textury v procentech.<br/>            Čtení/zápis **float**. |
| [`tile_scale_y`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_scale_y/) | Vrací nebo nastavuje svislé měřítko výplně textury v procentech.<br/>            Čtení/zápis **float**. |
| [`tile_alignment`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_alignment/) | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a jak se opakuje po celém tvaru.<br/>            Čtení/zápis [`RectangleAlignment`](/slides/python-net/cs/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/cs/aspose.slides/ipicturefillformat/tile_flip/) | Překlápí dlaždici textury kolem její vodorovné, svislé nebo obou os.<br/>            Čtení/zápis [`TileFlip`](/slides/python-net/cs/aspose.slides/tileflip). |

## Metody

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/cs/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/cs/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/cs/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Odstraňuje oříznuté oblasti výplňového obrázku. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)