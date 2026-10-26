---
title: IPortion class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/iportion/
---
## IPortion třída

Represents a portion of text inside a text paragraph.

The IPortion type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`portion_format`](/slides/python-net/cs/aspose.slides/iportion/portion_format/) | Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikovaného dědění.<br/>            Pouze pro čtení [`IPortionFormat`](/slides/python-net/cs/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/cs/aspose.slides/iportion/text/) | Získá nebo nastaví prostý text části.<br/>            Čtení/zápis **str**. |
| [`field`](/slides/python-net/cs/aspose.slides/iportion/field/) | Vrací pole této části.<br/>            Pouze pro čtení [`IField`](/slides/python-net/cs/aspose.slides/ifield). |
| [`slide`](/slides/python-net/cs/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/iportion/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/cs/aspose.slides/iportion/add_field/#ifieldtype) | Převede tuto část na automaticky aktualizované pole. |
| [`add_field(self, internal_string)`](/slides/python-net/cs/aspose.slides/iportion/add_field/#str) | Převede tuto část na automaticky aktualizované pole. |
| [`remove_field(self)`](/slides/python-net/cs/aspose.slides/iportion/remove_field/#) | Převede tuto část pole na jednoduchou část. |
| [`get_rect(self)`](/slides/python-net/cs/aspose.slides/iportion/get_rect/#) | Získá souřadnice obdélníku, který ohraničuje část. Obdélník zahrnuje všechny řádky<br/>             textu v části, včetně prázdných. |
| [`get_coordinates(self)`](/slides/python-net/cs/aspose.slides/iportion/get_coordinates/#) | Získá souřadnice začátku části. Souřadnice X bodu představuje začátek části od prvního znaku včetně levého postranního odsazení. Souřadnice Y zahrnuje horní postranní odsazení. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)