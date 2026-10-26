---
title: FontFallBackRule class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/fontfallbackrule/
---
## FontFallBackRule Klasse

Stellt die Font-Fallback-Regel dar

Der FontFallBackRule-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/de/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Erstellt eine neue Instanz. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/de/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Erstellt eine neue Instanz. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`range_start_index`](/slides/python-net/de/aspose.slides/fontfallbackrule/range_start_index/) | Liefert den ersten Index des zusammenhängenden Unicode-Bereichs. |
| [`range_end_index`](/slides/python-net/de/aspose.slides/fontfallbackrule/range_end_index/) | Liefert den letzten Index des zusammenhängenden Unicode-Bereichs. |
| [`count`](/slides/python-net/de/aspose.slides/fontfallbackrule/count/) | Liefert die tatsächlich für den Bereich definierten Schriftartenanzahl.<br/>            Nur lesbar **int**. |

Liefert den Schriftartnamen am angegebenen Index.  
            Nur lesbar [`IFontFallBackRule`](/slides/python-net/de/aspose.slides/ifontfallbackrule).

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/de/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Fügt neue(n) Font(s) zur Liste der FallBack-Schriftarten hinzu. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/de/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Fügt neue Schriftarten zur Liste der FallBack-Schriftarten hinzu. |
| [`to_array(self)`](/slides/python-net/de/aspose.slides/fontfallbackrule/to_array/#) | Erstellt und gibt ein Array mit allen FallBack-Schriftarten für diese Regel zurück. |
| [`to_array(self, start_index, count)`](/slides/python-net/de/aspose.slides/fontfallbackrule/to_array/#int-int) | Erstellt und gibt ein Array mit allen FallBack-Schriftarten aus dem angegebenen Bereich in der Liste zurück. |
| [`clear(self)`](/slides/python-net/de/aspose.slides/fontfallbackrule/clear/#) | Entfernt alle Schriftarten aus der Liste. |
| [`remove(self, font_name)`](/slides/python-net/de/aspose.slides/fontfallbackrule/remove/#str) | Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/fontfallbackrule/remove_at/#int) | Entfernt die FallBack-Schriftart am angegebenen Index der Liste. |
| [`index_of(self, font_name)`](/slides/python-net/de/aspose.slides/fontfallbackrule/index_of/#str) | Gibt einen Index der angegebenen Regel in der Sammlung zurück. |

### Siehe auch
* Klasse [`IFontFallBackRule`](/slides/python-net/de/aspose.slides/ifontfallbackrule)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)