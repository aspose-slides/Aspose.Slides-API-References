---
title: FontFallBackRule class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/fontfallbackrule/
---
## FontFallBackRule třída

Reprezentuje pravidlo náhradního písma

Typ FontFallBackRule vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Vytvoří novou instanci. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Vytvoří novou instanci. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`range_start_index`](/slides/python-net/cs/aspose.slides/fontfallbackrule/range_start_index/) | Získá první index souvislého unicode rozsahu. |
| [`range_end_index`](/slides/python-net/cs/aspose.slides/fontfallbackrule/range_end_index/) | Získá poslední index souvislého unicode rozsahu. |
| [`count`](/slides/python-net/cs/aspose.slides/fontfallbackrule/count/) | Získá počet fontů skutečně definovaných pro rozsah.<br/>            Pouze pro čtení **int**. |

Získá název fontu na zadaném indexu.
            Pouze pro čtení [`IFontFallBackRule`](/slides/python-net/cs/aspose.slides/ifontfallbackrule).

## Indexer

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Přidá nový font(y) do seznamu náhradních fontů. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Přidá nové fonty do seznamu náhradních fontů. |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/to_array/#) | Vytvoří a vrátí pole se všemi náhradními fonty pro toto pravidlo. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/to_array/#int-int) | Vytvoří a vrátí pole se všemi náhradními fonty ze zadaného rozsahu v seznamu. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/clear/#) | Odstraní všechny fonty ze seznamu. |
| [`remove(self, font_name)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/remove/#str) | Odstraní první výskyt konkrétního náhradního fontu ze seznamu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/remove_at/#int) | Odstraní náhradní font na zadaném indexu v seznamu. |
| [`index_of(self, font_name)`](/slides/python-net/cs/aspose.slides/fontfallbackrule/index_of/#str) | Vrátí index specifikovaného pravidla ve sbírce. |

### Viz také
* třída [`IFontFallBackRule`](/slides/python-net/cs/aspose.slides/ifontfallbackrule)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)