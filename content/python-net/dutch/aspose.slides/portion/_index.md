---
title: Portion class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/portion/
---
## Portion klasse

Stelt een gedeelte van tekst voor in een tekstparagraaf.

Het type Portion exposeert de volgende leden:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/portion/__init__/#) | Initialiseert een nieuw exemplaar van de class Portion. |
| [`__init__(self, str)`](/slides/python-net/nl/aspose.slides/portion/__init__/#str) | Initialiseert een nieuw exemplaar van de class Portion. |
| [`__init__(self, portion)`](/slides/python-net/nl/aspose.slides/portion/__init__/#portion) | Initialiseert een nieuw exemplaar van de class Portion. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`portion_format`](/slides/python-net/nl/aspose.slides/portion/portion_format/) | Retourneert een opmaakobject dat de expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat zonder overerving toegepast.<br/>            Alleen-lezen [`IPortionFormat`](/slides/python-net/nl/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/nl/aspose.slides/portion/text/) | Haalt de platte tekst van een gedeelte op of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`field`](/slides/python-net/nl/aspose.slides/portion/field/) | Retourneert een veld van dit gedeelte.<br/>            Alleen-lezen [`IField`](/slides/python-net/nl/aspose.slides/ifield). |
| [`slide`](/slides/python-net/nl/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/portion/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/nl/aspose.slides/portion/add_field/#ifieldtype) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [`add_field(self, internal_string)`](/slides/python-net/nl/aspose.slides/portion/add_field/#str) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [`remove_field(self)`](/slides/python-net/nl/aspose.slides/portion/remove_field/#) | Converteert dit veldgedeelte naar het eenvoudige gedeelte. |
| [`get_rect(self)`](/slides/python-net/nl/aspose.slides/portion/get_rect/#) | Haal de coördinaten op van de rechthoek die het gedeelte begrenst. De rechthoek omvat alle regels van<br/>             tekst in het gedeelte, inclusief lege regels. |
| [`get_coordinates(self)`](/slides/python-net/nl/aspose.slides/portion/get_coordinates/#) | Haal de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt vertegenwoordigt het begin van het gedeelte vanaf het eerste teken inclusief de linker-side bearing. De Y-coördinaat omvat de boven-side bearing. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)