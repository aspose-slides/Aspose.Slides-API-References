---
title: Portion class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/portion/
---
## Portion třída

Představuje část textu uvnitř odstavce textu.

Typ Portion vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/portion/__init__/#) | Inicializuje novou instanci třídy Portion. |
| [`__init__(self, str)`](/slides/python-net/cs/aspose.slides/portion/__init__/#str) | Inicializuje novou instanci třídy Portion. |
| [`__init__(self, portion)`](/slides/python-net/cs/aspose.slides/portion/__init__/#portion) | Inicializuje novou instanci třídy Portion. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`portion_format`](/slides/python-net/cs/aspose.slides/portion/portion_format/) | Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování části textu bez dědičnosti.<br/>            Pouze pro čtení [`IPortionFormat`](/slides/python-net/cs/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/cs/aspose.slides/portion/text/) | Získává nebo nastavuje prostý text části.<br/>            Čtení/zápis **str**. |
| [`field`](/slides/python-net/cs/aspose.slides/portion/field/) | Vrací pole této části.<br/>            Pouze pro čtení [`IField`](/slides/python-net/cs/aspose.slides/ifield). |
| [`slide`](/slides/python-net/cs/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/portion/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/cs/aspose.slides/portion/add_field/#ifieldtype) | Převádí tuto část na automaticky aktualizované pole. |
| [`add_field(self, internal_string)`](/slides/python-net/cs/aspose.slides/portion/add_field/#str) | Převádí tuto část na automaticky aktualizované pole. |
| [`remove_field(self)`](/slides/python-net/cs/aspose.slides/portion/remove_field/#) | Převádí tuto část pole na jednoduchou část. |
| [`get_rect(self)`](/slides/python-net/cs/aspose.slides/portion/get_rect/#) | Získá souřadnice obdélníku, který ohraničuje část. Obdélník zahrnuje všechny řádky<br/>             textu v části, včetně prázdných. |
| [`get_coordinates(self)`](/slides/python-net/cs/aspose.slides/portion/get_coordinates/#) | Získá souřadnice počátku části. X-souřadnice bodu představuje začátek části od prvního znaku včetně levého okraje. Y-souřadnice zahrnuje horní okraj. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)