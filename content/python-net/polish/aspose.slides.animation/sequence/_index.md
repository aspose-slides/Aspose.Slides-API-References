---
title: Sequence class
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.animation/sequence/
---
## Sequence klasa

Reprezentuje sekwencję (kolekcję efektów).

Typ Sequence udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`count`](/slides/python-net/pl/aspose.slides.animation/sequence/count/) | Zwraca liczbę efektów w sekwencji.<br/>            Tylko do odczytu **int**. |
| [`trigger_shape`](/slides/python-net/pl/aspose.slides.animation/sequence/trigger_shape/) | Zwraca lub ustawia docelowy kształt dla INTERACTIVE sekwencji.<br/>            Jeśli sekwencja nie jest interaktywna, zwraca None.<br/>            Odczyt/zapis [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |

Zwraca efekt o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.animation/sequence/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/pl/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Dodaje nowy efekt na koniec sekwencji. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/pl/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Dodaje nowy efekt animacji dla akapitu na koniec sekwencji. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/pl/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/pl/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji. |
| [`remove(self, item)`](/slides/python-net/pl/aspose.slides.animation/sequence/remove/#ieffect) | Usuwa określony efekt z kolekcji. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides.animation/sequence/remove_at/#int) | Usuwa efekt z kolekcji. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides.animation/sequence/clear/#) | Usuwa wszystkie efekty z kolekcji. |
| [`remove_by_shape(self, shape)`](/slides/python-net/pl/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Usuwa efekt dla określonego kształtu. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/pl/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Zwraca tablicę efektów dla określonego kształtu. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/pl/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Zwraca tablicę efektów dla określonego akapitu. |
| [`get_count(self, shape)`](/slides/python-net/pl/aspose.slides.animation/sequence/get_count/#ishape) | Zwraca liczbę efektów dla określonego kształtu. |

### Zobacz także
* moduł [`aspose.slides.animation`](/slides/python-net/pl/aspose.slides.animation)
* biblioteka [`Aspose.Slides`](/slides/python-net)