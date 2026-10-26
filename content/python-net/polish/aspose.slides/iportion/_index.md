---
title: IPortion class
second_title: Aspose.Slides dla Pythona przez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides/iportion/
---
## IPortion klasa

Reprezentuje fragment tekstu wewnątrz akapitu tekstowego.

Typ IPortion udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`portion_format`](/slides/python-net/pl/aspose.slides/iportion/portion_format/) | Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanej dziedziczenia.<br/>            Tylko do odczytu [`IPortionFormat`](/slides/python-net/pl/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pl/aspose.slides/iportion/text/) | Pobiera lub ustawia zwykły tekst fragmentu.<br/>            Odczyt/zapis **str**. |
| [`field`](/slides/python-net/pl/aspose.slides/iportion/field/) | Zwraca pole tego fragmentu.<br/>            Tylko do odczytu [`IField`](/slides/python-net/pl/aspose.slides/ifield). |
| [`slide`](/slides/python-net/pl/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/iportion/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pl/aspose.slides/iportion/add_field/#ifieldtype) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [`add_field(self, internal_string)`](/slides/python-net/pl/aspose.slides/iportion/add_field/#str) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [`remove_field(self)`](/slides/python-net/pl/aspose.slides/iportion/remove_field/#) | Konwertuje ten fragment pola na prosty fragment. |
| [`get_rect(self)`](/slides/python-net/pl/aspose.slides/iportion/get_rect/#) | Pobiera współrzędne prostokąta otaczającego fragment. Prostokąt obejmuje wszystkie linie<br/>             tekstu w fragmencie, w tym puste. |
| [`get_coordinates(self)`](/slides/python-net/pl/aspose.slides/iportion/get_coordinates/#) | Pobiera współrzędne początku fragmentu. Współrzędna X punktu reprezentuje początek fragmentu od pierwszego znaku, uwzględniając lewy odstęp boczny.<br/>            Współrzędna Y <br/>            obejmuje górny odstęp boczny. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)