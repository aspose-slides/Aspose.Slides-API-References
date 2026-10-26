---
title: MathPortion class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathportion/
---
## MathPortion klasa

Reprezentuje fragment z kontekstem matematycznym.

**Dziedziczenie:**[`MathPortion`](/slides/python-net/pl/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/pl/aspose.slides/portion)

Typ MathPortion udostępnia następujących członków:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/__init__/#) | Inicjalizuje nową instancję klasy MathPortion. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`portion_format`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/portion_format/) | Zwraca obiekt formatowania, który zawiera explicite ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia.<br/>            Tylko do odczytu [`IPortionFormat`](/slides/python-net/pl/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/text/) | Pobiera lub ustawia zwykły tekst fragmentu.<br/>            Odczyt/zapis **str**. |
| [`field`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/field/) | Zwraca pole tego fragmentu.<br/>            Tylko do odczytu [`IField`](/slides/python-net/pl/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/math_paragraph/) | Akapit matematyczny |
| [`slide`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [`add_field(self, internal_string)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/add_field/#str) | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| [`remove_field(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/remove_field/#) | Konwertuje ten fragment pola na prosty fragment. |
| [`get_rect(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/get_rect/#) | Pobiera współrzędne prostokąta, który ogranicza fragment. Prostokąt obejmuje wszystkie linie<br/>             tekstu w fragmencie, w tym puste. |
| [`get_coordinates(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/get_coordinates/#) | Pobiera współrzędne początku fragmentu. Współrzędna X punktu reprezentuje początek fragmentu od pierwszego znaku, włącznie z lewym marginesem. <br/>            Współrzędna Y obejmuje górny margines. |

### Zobacz także
* klasa [`MathPortion`](/slides/python-net/pl/aspose.slides.mathtext/mathportion)
* klasa [`Portion`](/slides/python-net/pl/aspose.slides/portion)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)