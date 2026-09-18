---
title: FontFallBackRule class
second_title: Aspose.Slides dla Pythona przez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/fontfallbackrule/
---
## FontFallBackRule class

Reprezentuje regułę zastępowania czcionki

Typ FontFallBackRule udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Tworzy nową instancję. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Tworzy nową instancję. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`range_start_index`](/slides/python-net/pl/aspose.slides/fontfallbackrule/range_start_index/) | Pobiera pierwszy indeks ciągłego zakresu Unicode. |
| [`range_end_index`](/slides/python-net/pl/aspose.slides/fontfallbackrule/range_end_index/) | Pobiera ostatni indeks ciągłego zakresu Unicode. |
| [`count`](/slides/python-net/pl/aspose.slides/fontfallbackrule/count/) | Zwraca liczbę czcionek faktycznie zdefiniowanych dla zakresu.<br/>            Tylko do odczytu **int**. |

Zwraca nazwę czcionki pod określonym indeksem.
            Tylko do odczytu [`IFontFallBackRule`](/slides/python-net/pl/aspose.slides/ifontfallbackrule).

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Dodaje nową czcionkę(y) do listy czcionek zastępczych. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Dodaje nowe czcionki do listy czcionek zastępczych. |
| [`to_array(self)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/to_array/#) | Tworzy i zwraca tablicę ze wszystkimi czcionkami zastępczymi dla tej reguły. |
| [`to_array(self, start_index, count)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/to_array/#int-int) | Tworzy i zwraca tablicę ze wszystkimi czcionkami zastępczymi z określonego zakresu na liście. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/clear/#) | Usuwa wszystkie czcionki z listy. |
| [`remove(self, font_name)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/remove/#str) | Usuwa pierwsze wystąpienie określonej czcionki zastępczej z listy. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/remove_at/#int) | Usuwa czcionkę zastępczą pod określonym indeksem na liście. |
| [`index_of(self, font_name)`](/slides/python-net/pl/aspose.slides/fontfallbackrule/index_of/#str) | Zwraca indeks określonej reguły w kolekcji. |


### Zobacz też
* klasa [`IFontFallBackRule`](/slides/python-net/pl/aspose.slides/ifontfallbackrule)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)