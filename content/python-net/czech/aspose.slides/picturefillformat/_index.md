---
title: PictureFillFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenčních dokumentů API
description: 
type: docs
url: /cs/aspose.slides/picturefillformat/
---
## PictureFillFormat třída

Představuje styl výplně obrázkem.

**Dědičnost:**[`PictureFillFormat`](/slides/python-net/cs/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ PictureFillFormat zveřejňuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`dpi`](/slides/python-net/cs/aspose.slides/picturefillformat/dpi/) | Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku.<br/>            Read/write **int**. |
| [`picture_fill_mode`](/slides/python-net/cs/aspose.slides/picturefillformat/picture_fill_mode/) | Vrací nebo nastavuje režim vyplnění obrázkem.<br/>            Read/write [`PictureFillMode`](/slides/python-net/cs/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/cs/aspose.slides/picturefillformat/picture/) | Vrací obrázek.<br/>            Read-only [`ISlidesPicture`](/slides/python-net/cs/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/cs/aspose.slides/picturefillformat/crop_left/) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku.<br/>            Read/write **float**. |
| [`crop_top`](/slides/python-net/cs/aspose.slides/picturefillformat/crop_top/) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta z horní strany obrázku.<br/>            Read/write **float**. |
| [`crop_right`](/slides/python-net/cs/aspose.slides/picturefillformat/crop_right/) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku.<br/>            Read/write **float**. |
| [`crop_bottom`](/slides/python-net/cs/aspose.slides/picturefillformat/crop_bottom/) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, která je oříznuta ze spodní strany obrázku.<br/>            Read/write **float**. |
| [`stretch_offset_left`](/slides/python-net/cs/aspose.slides/picturefillformat/stretch_offset_left/) | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunutím od levého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, zatímco záporné procento udává vnější odsazení.<br/>            Read/write **float**. |
| [`stretch_offset_top`](/slides/python-net/cs/aspose.slides/picturefillformat/stretch_offset_top/) | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunutím od horního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, zatímco záporné procento udává vnější odsazení.<br/>            Read/write **float**. |
| [`stretch_offset_right`](/slides/python-net/cs/aspose.slides/picturefillformat/stretch_offset_right/) | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunutím od pravého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, zatímco záporné procento udává vnější odsazení.<br/>            Read/write **float**. |
| [`stretch_offset_bottom`](/slides/python-net/cs/aspose.slides/picturefillformat/stretch_offset_bottom/) | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunutím od spodního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, zatímco záporné procento udává vnější odsazení.<br/>            Read/write **float**. |
| [`tile_offset_x`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_offset_x/) | Vrací nebo nastavuje horizontální odsazení textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva.<br/>            Read/write **float**. |
| [`tile_offset_y`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_offset_y/) | Vrací nebo nastavuje vertikální odsazení textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná hodnota ji posouvá nahoru.<br/>            Read/write **float**. |
| [`tile_scale_x`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_scale_x/) | Vrací nebo nastavuje horizontální měřítko výplně textury jako procento.<br/>            Read/write **float**. |
| [`tile_scale_y`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_scale_y/) | Vrací nebo nastavuje vertikální měřítko výplně textury jako procento.<br/>            Read/write **float**. |
| [`tile_alignment`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_alignment/) | Vrací nebo nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí počáteční bod vzoru textury a způsob, jakým se opakuje po celém tvaru.<br/>            Read/write [`RectangleAlignment`](/slides/python-net/cs/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/cs/aspose.slides/picturefillformat/tile_flip/) | Otáčí dlaždici textury kolem jejího horizontálního, vertikálního nebo obou os.<br/>            Read/write [`TileFlip`](/slides/python-net/cs/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/cs/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/picturefillformat/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/cs/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a specifikovaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/cs/aspose.slides/picturefillformat/compress_image/#bool-float) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a specifikovaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/cs/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | Odstraňuje oříznuté oblasti výplňového obrázku. |

### Viz také
* třída [`PictureFillFormat`](/slides/python-net/cs/aspose.slides/picturefillformat)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)