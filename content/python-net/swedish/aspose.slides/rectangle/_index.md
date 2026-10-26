---
title: Rectangle class
second_title: Aspose.Slides för Python via .NET API-referens
description: Lagrar en uppsättning av fyra heltal som representerar rektangelns plats och storlek.
type: docs
url: /sv/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle klass

Lagrar en uppsättning av fyra heltal som representerar placeringen och storleken på en rektangel. Kompatibel med .NET `System.Drawing.Rectangle`.

Rectangle-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/sv/aspose.slides/rectangle/__init__/#int-int-int-int) | Skapar en rektangel med den angivna platsen och storleken.<br/>            Float-värden avkortas till heltal. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x`](/slides/python-net/sv/aspose.slides/rectangle/x/) | Hämtar x-koordinaten för det övre vänstra hörnet av denna rektangel.<br/>            Skrivskyddad **int**. |
| [`y`](/slides/python-net/sv/aspose.slides/rectangle/y/) | Hämtar y-koordinaten för det övre vänstra hörnet av denna rektangel.<br/>            Skrivskyddad **int**. |
| [`width`](/slides/python-net/sv/aspose.slides/rectangle/width/) | Hämtar bredden av denna rektangel.<br/>            Skrivskyddad **int**. |
| [`height`](/slides/python-net/sv/aspose.slides/rectangle/height/) | Hämtar höjden av denna rektangel.<br/>            Skrivskyddad **int**. |
| [`left`](/slides/python-net/sv/aspose.slides/rectangle/left/) | Hämtar x-koordinaten för vänsterkanten av denna rektangel. Är lika med `x`.<br/>            Skrivskyddad **int**. |
| [`top`](/slides/python-net/sv/aspose.slides/rectangle/top/) | Hämtar y-koordinaten för överkanten av denna rektangel. Är lika med `y`.<br/>            Skrivskyddad **int**. |
| [`right`](/slides/python-net/sv/aspose.slides/rectangle/right/) | Hämtar x-koordinaten som är summan av `x` och `width` för denna rektangel.<br/>            Skrivskyddad **int**. |
| [`bottom`](/slides/python-net/sv/aspose.slides/rectangle/bottom/) | Hämtar y-koordinaten som är summan av `y` och `height` för denna rektangel.<br/>            Skrivskyddad **int**. |
| [`is_empty`](/slides/python-net/sv/aspose.slides/rectangle/is_empty/) | Anger om alla numeriska egenskaper för denna rektangel har värdet noll.<br/>            Skrivskyddad **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/sv/aspose.slides/rectangle/contains/#int-int) | Avgör om den angivna punkten finns inom denna rektangel. |
| [`contains(self, point)`](/slides/python-net/sv/aspose.slides/rectangle/contains/#point) | Avgör om den angivna punkten finns inom denna rektangel. |
| [`contains(self, rect)`](/slides/python-net/sv/aspose.slides/rectangle/contains/#rectangle) | Avgör om det rektangulära område som representeras av `rect` är helt innehållet inom denna rektangel. |


### Anmärkningar

Rektanglar jämförs efter deras plats och storlek med `==` och kan användas som nycklar i ordböcker eller som medlemmar i mängder.


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)