---
title: FontFallBackRule class
second_title: Aspose.Slides Python számára .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/fontfallbackrule/
---
## FontFallBackRule osztály

A betűtípus-helyettesítési szabályt képviseli

A FontFallBackRule típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Új példányt hoz létre. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Új példányt hoz létre. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`range_start_index`](/slides/python-net/hu/aspose.slides/fontfallbackrule/range_start_index/) | Az egymást követő Unicode-tartomány első indexének lekérése. |
| [`range_end_index`](/slides/python-net/hu/aspose.slides/fontfallbackrule/range_end_index/) | Az egymást követő Unicode-tartomány utolsó indexének lekérése. |
| [`count`](/slides/python-net/hu/aspose.slides/fontfallbackrule/count/) | A tartományhoz ténylegesen meghatározott betűtípusok számának lekérése.<br/>            Read-only **int**. |

A megadott indexnél a betűtípus nevét adja vissza.  
Csak olvasható [`IFontFallBackRule`](/slides/python-net/hu/aspose.slides/ifontfallbackrule).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Új betűtípust (új betűtípusokat) ad hozzá a FallBack betűtípusok listájához. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Új betűtípusokat ad hozzá a FallBack betűtípusok listájához. |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/to_array/#) | Létrehoz és visszaad egy tömböt, amely az összes FallBack betűtípust tartalmazza ehhez a szabályhoz. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/to_array/#int-int) | Létrehoz és visszaad egy tömböt, amely a listában a megadott tartományból származó összes FallBack betűtípust tartalmazza. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/clear/#) | Eltávolítja az összes betűtípust a listáról. |
| [`remove(self, font_name)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/remove/#str) | Eltávolítja a specifikus FallBack betűtípus első előfordulását a listáról. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/remove_at/#int) | Eltávolítja a listában a megadott indexnél lévő FallBack betűtípust. |
| [`index_of(self, font_name)`](/slides/python-net/hu/aspose.slides/fontfallbackrule/index_of/#str) | Visszaadja a megadott szabály indexét a gyűjteményben. |

### Lásd még
* osztály [`IFontFallBackRule`](/slides/python-net/hu/aspose.slides/ifontfallbackrule)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)