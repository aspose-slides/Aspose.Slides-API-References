---
title: IPictureFillFormat class
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klasa

Reprezentuje styl wypełnienia obrazem.

Typ IPictureFillFormat udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`dpi`](/slides/python-net/pl/aspose.slides/ipicturefillformat/dpi/) | Zwraca lub ustawia dpi używane do wypełniania obrazu.<br/>            Odczyt/zapis **int**. |
| [`picture_fill_mode`](/slides/python-net/pl/aspose.slides/ipicturefillformat/picture_fill_mode/) | Zwraca lub ustawia tryb wypełniania obrazem.<br/>            Odczyt/zapis [`PictureFillMode`](/slides/python-net/pl/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/pl/aspose.slides/ipicturefillformat/picture/) | Zwraca obraz.<br/>            Tylko odczyt [`ISlidesPicture`](/slides/python-net/pl/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/pl/aspose.slides/ipicturefillformat/crop_left/) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po lewej stronie obrazu. <br/>            Odczyt/zapis **float**. |
| [`crop_top`](/slides/python-net/pl/aspose.slides/ipicturefillformat/crop_top/) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od góry obrazu. <br/>            Odczyt/zapis **float**. |
| [`crop_right`](/slides/python-net/pl/aspose.slides/ipicturefillformat/crop_right/) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po prawej stronie obrazu. <br/>            Odczyt/zapis **float**. |
| [`crop_bottom`](/slides/python-net/pl/aspose.slides/ipicturefillformat/crop_bottom/) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte od dołu obrazu. <br/>            Odczyt/zapis **float**. |
| [`stretch_offset_left`](/slides/python-net/pl/aspose.slides/ipicturefillformat/stretch_offset_left/) | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia określoną przez offset procentowy od lewej krawędzi ramki kształtu.<br/>            Dodatni procent określa wcięcie, a ujemny procent określa występ.<br/>            Odczyt/zapis **float**. |
| [`stretch_offset_top`](/slides/python-net/pl/aspose.slides/ipicturefillformat/stretch_offset_top/) | Zwraca lub ustawia górną krawędź prostokąta wypełnienia określoną przez offset procentowy od górnej krawędzi ramki kształtu.<br/>            Dodatni procent określa wcięcie, a ujemny procent określa występ.<br/>            Odczyt/zapis **float**. |
| [`stretch_offset_right`](/slides/python-net/pl/aspose.slides/ipicturefillformat/stretch_offset_right/) | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia określoną przez offset procentowy od prawej krawędzi ramki kształtu.<br/>            Dodatni procent określa wcięcie, a ujemny procent określa występ.<br/>            Odczyt/zapis **float**. |
| [`stretch_offset_bottom`](/slides/python-net/pl/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia określoną przez offset procentowy od dolnej krawędzi ramki kształtu.<br/>            Dodatni procent określa wcięcie, a ujemny procent określa występ.<br/>            Odczyt/zapis **float**. |
| [`tile_offset_x`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_offset_x/) | Zwraca lub ustawia poziomy offset tekstury od pochodzenia kształtu w punktach.<br/>             Dodatnia wartość przesuwa teksturę w prawo, a ujemna w lewo.<br/>             Odczyt/zapis **float**. |
| [`tile_offset_y`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_offset_y/) | Zwraca lub ustawia pionowy offset tekstury od pochodzenia kształtu w punktach.<br/>             Dodatnia wartość przesuwa teksturę w dół, a ujemna w górę.<br/>             Odczyt/zapis **float**. |
| [`tile_scale_x`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_scale_x/) | Zwraca lub ustawia poziomą skalę wypełnienia teksturą jako procent.<br/>             Odczyt/zapis **float**. |
| [`tile_scale_y`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_scale_y/) | Zwraca lub ustawia pionową skalę wypełnienia teksturą jako procent.<br/>             Odczyt/zapis **float**. |
| [`tile_alignment`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_alignment/) | Zwraca lub ustawia sposób wyrównania tekstury w obrębie kształtu. Ustawienie to kontroluje punkt początkowy wzoru tekstury oraz sposób jego powtarzania w kształcie.<br/>             Odczyt/zapis [`RectangleAlignment`](/slides/python-net/pl/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/pl/aspose.slides/ipicturefillformat/tile_flip/) | Odwraca kafelek tekstury wzdłuż osi poziomej, pionowej lub obu.<br/>             Odczyt/zapis [`TileFlip`](/slides/python-net/pl/aspose.slides/tileflip). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/pl/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/pl/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/pl/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Usuwa przycięte obszary wypełnionego obrazu. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)