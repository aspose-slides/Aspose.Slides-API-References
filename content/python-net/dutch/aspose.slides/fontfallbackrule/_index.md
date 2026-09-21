---
title: FontFallBackRule class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/fontfallbackrule/
---
## FontFallBackRule klasse

Stelt een lettertypefallbackregel voor

Het type FontFallBackRule biedt de volgende leden weer:

## Constructoren

| Constructor | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Maakt een nieuw exemplaar aan. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Maakt een nieuw exemplaar aan. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/nl/aspose.slides/fontfallbackrule/range_start_index/) | Haalt de eerste index van een doorlopende Unicode-reeks op. |
| [`range_end_index`](/slides/python-net/nl/aspose.slides/fontfallbackrule/range_end_index/) | Haalt de laatste index van een doorlopende Unicode-reeks op. |
| [`count`](/slides/python-net/nl/aspose.slides/fontfallbackrule/count/) | Haalt het aantal lettertypen op dat daadwerkelijk voor het bereik is gedefinieerd.<br/>            Alleen-lezen **int**. |

Haalt de lettertype-naam op op de opgegeven index.<br/>            Alleen-lezen [`IFontFallBackRule`](/slides/python-net/nl/aspose.slides/ifontfallbackrule).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Voegt een nieuw(e) lettertype(s) toe aan de lijst met FallBack-lettertypen. |
| [`to_array(self)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/to_array/#) | Maakt een array aan en retourneert deze met alle FallBack-lettertypen voor deze regel. |
| [`to_array(self, start_index, count)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/to_array/#int-int) | Maakt een array aan en retourneert deze met alle FallBack-lettertypen van het opgegeven bereik in de lijst. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/clear/#) | Verwijdert alle lettertypen uit de lijst. |
| [`remove(self, font_name)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/remove/#str) | Verwijdert de eerste voorkoming van een specifiek FallBack-lettertype uit de lijst. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/remove_at/#int) | Verwijdert het FallBack-lettertype op de opgegeven index in de lijst. |
| [`index_of(self, font_name)`](/slides/python-net/nl/aspose.slides/fontfallbackrule/index_of/#str) | Retourneert een index van de opgegeven regel in de collectie. |


### Zie ook
* klasse [`IFontFallBackRule`](/slides/python-net/nl/aspose.slides/ifontfallbackrule)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)