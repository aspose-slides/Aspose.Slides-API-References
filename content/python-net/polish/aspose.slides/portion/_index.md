---
title: Portion class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/portion/
---
## Portion klasa

Reprezentuje fragment tekstu wewnątrz akapitu tekstowego.

Typ Portion udostępnia następujące elementy:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/portion/__init__/#) | Inicjalizuje nową instancję klasy Portion. |
| [`__init__(self, str)`](/slides/python-net/pl/aspose.slides/portion/__init__/#str) | Inicjalizuje nową instancję klasy Portion. |
| [`__init__(self, portion)`](/slides/python-net/pl/aspose.slides/portion/__init__/#portion) | Inicjalizuje nową instancję klasy Portion. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`portion_format`](/slides/python-net/pl/aspose.slides/portion/portion_format/) | Zwraca obiekt formatowania, który zawiera explicite ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia.<br/>            Tylko do odczytu [`IPortionFormat`](/slides/python-net/pl/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pl/aspose.slides/portion/text/) | Pobiera lub ustawia zwykły tekst części.<br/>            Odczyt/zapis **str**. |
| [`field`](/slides/python-net/pl/aspose.slides/portion/field/) | Zwraca pole tej części.<br/>            Tylko do odczytu [`IField`](/slides/python-net/pl/aspose.slides/ifield). |
| [`slide`](/slides/python-net/pl/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/portion/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pl/aspose.slides/portion/add_field/#ifieldtype) | Konwertuje tę część na automatycznie aktualizowane pole. |
| [`add_field(self, internal_string)`](/slides/python-net/pl/aspose.slides/portion/add_field/#str) | Konwertuje tę część na automatycznie aktualizowane pole. |
| [`remove_field(self)`](/slides/python-net/pl/aspose.slides/portion/remove_field/#) | Konwertuje tę część pola na prostą część. |
| [`get_rect(self)`](/slides/python-net/pl/aspose.slides/portion/get_rect/#) | Pobiera współrzędne prostokąta otaczającego część. Prostokąt obejmuje wszystkie wiersze<br/>            tekstu w części, włącznie z pustymi. |
| [`get_coordinates(self)`](/slides/python-net/pl/aspose.slides/portion/get_coordinates/#) | Pobiera współrzędne początku części. Współrzędna X punktu reprezentuje <br/>            początek części od pierwszego znaku, włącznie z lewym marginesem. Współrzędna Y <br/>            zawiera górny margines. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)