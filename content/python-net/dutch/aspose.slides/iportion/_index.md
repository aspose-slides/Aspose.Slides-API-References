---
title: IPortion class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iportion/
---
## IPortion klasse

Stelt een tekstgedeelte binnen een tekstparagraaf voor.

Het IPortion-type exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`portion_format`](/slides/python-net/nl/aspose.slides/iportion/portion_format/) | Retourneert opmaakobject dat expliciet ingestelde opmaak eigenschappen van het tekstgedeelte bevat zonder dat er overerving wordt toegepast.<br/>            Alleen-lezen [`IPortionFormat`](/slides/python-net/nl/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/nl/aspose.slides/iportion/text/) | Haalt de platte tekst van een gedeelte op of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`field`](/slides/python-net/nl/aspose.slides/iportion/field/) | Retourneert een veld van dit gedeelte.<br/>            Alleen-lezen [`IField`](/slides/python-net/nl/aspose.slides/ifield). |
| [`slide`](/slides/python-net/nl/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/iportion/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/nl/aspose.slides/iportion/add_field/#ifieldtype) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [`add_field(self, internal_string)`](/slides/python-net/nl/aspose.slides/iportion/add_field/#str) | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| [`remove_field(self)`](/slides/python-net/nl/aspose.slides/iportion/remove_field/#) | Converteert dit veldgedeelte naar het eenvoudige gedeelte. |
| [`get_rect(self)`](/slides/python-net/nl/aspose.slides/iportion/get_rect/#) | Haal de coördinaten op van het rechthoek dat het gedeelte begrenst. Het rechthoek omvat alle regels van<br/>             tekst in het gedeelte, inclusief lege regels. |
| [`get_coordinates(self)`](/slides/python-net/nl/aspose.slides/iportion/get_coordinates/#) | Haal de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt geeft het begin van het gedeelte weer vanaf het eerste teken inclusief de linkerzijde draagwijdte. De Y-coördinaat omvat de bovenkant draagwijdte. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)