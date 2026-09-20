---
title: Metered class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/metered/
---
## Metered klass

Tillhandahåller metoder för att sätta metered-nyckel.

Metered-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/metered/__init__/#) | Initierar en ny instans av den här klassen. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/sv/aspose.slides/metered/set_metered_key/#str-str) | Ställer in metered offentliga och privata nyckel.<br/>            Om du köper en metered-licens, bör detta API anropas när applikationen startas, normalt är detta tillräckligt. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, sätts licensen till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, om den är i utvärderingsstatus, anropa detta API igen. |
| [`get_consumption_quantity()`](/slides/python-net/sv/aspose.slides/metered/get_consumption_quantity/#) | Hämtar förbrukningsfilens storlek |
| [`get_consumption_credit()`](/slides/python-net/sv/aspose.slides/metered/get_consumption_credit/#) | Hämtar förbrukningskredit |
| [`get_product_name(self)`](/slides/python-net/sv/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/sv/aspose.slides/metered/is_metered_licensed/#) | Kontrollera om metered är licensierad |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)