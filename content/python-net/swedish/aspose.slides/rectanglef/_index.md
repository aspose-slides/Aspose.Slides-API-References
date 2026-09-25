---
title: RectangleF class
second_title: Aspose.Slides för Python via .NET API-referens
description: Lagrar en uppsättning av fyra flyttal som representerar placeringen och storleken på en rektangel.
type: docs
url: /sv/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF klass

Stores a set of four floating-point numbers that represent the location and size of a rectangle. Compatible with .NET `System.Drawing.RectangleF`.

**Inheritance:**[`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/sv/aspose.slides/rectangle)

The RectangleF type exposes the following members:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/sv/aspose.slides/rectanglef/__init__/#float-float-float-float) | Creates a rectangle with the specified location and size. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`x`](/slides/python-net/sv/aspose.slides/rectanglef/x/) | Hämtar x-koordinaten för det övre vänstra hörnet av denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/rectanglef/y/) | Hämtar y-koordinaten för det övre vänstra hörnet av denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/rectanglef/width/) | Hämtar bredden på denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/rectanglef/height/) | Hämtar höjden på denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`left`](/slides/python-net/sv/aspose.slides/rectanglef/left/) | Hämtar x-koordinaten för vänstra kanten av denna rektangel. Är lika med `x`.<br/>            **Skrivskyddad** **float**. |
| [`top`](/slides/python-net/sv/aspose.slides/rectanglef/top/) | Hämtar y-koordinaten för övre kanten av denna rektangel. Är lika med `y`.<br/>            **Skrivskyddad** **float**. |
| [`right`](/slides/python-net/sv/aspose.slides/rectanglef/right/) | Hämtar x-koordinaten som är summan av `x` och `width` för denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`bottom`](/slides/python-net/sv/aspose.slides/rectanglef/bottom/) | Hämtar y-koordinaten som är summan av `y` och `height` för denna rektangel.<br/>            **Skrivskyddad** **float**. |
| [`is_empty`](/slides/python-net/sv/aspose.slides/rectanglef/is_empty/) | Anger om alla numeriska egenskaper för denna rektangel har värdet noll.<br/>            **Skrivskyddad** **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/sv/aspose.slides/rectanglef/contains/#float-float) | Avgör om den angivna punkten finns inom denna rektangel. |
| [`contains(self, point)`](/slides/python-net/sv/aspose.slides/rectanglef/contains/#pointf) | Avgör om den angivna punkten finns inom denna rektangel. |
| [`contains(self, rect)`](/slides/python-net/sv/aspose.slides/rectanglef/contains/#rectanglef) | Avgör om det rektangulära området som representeras av `rect` är helt innehållet i denna rektangel. |


### Anmärkningar

Rektanglar jämförs med deras position och storlek med `==` och kan användas som nycklar i ordböcker eller som set-medlemmar.


### Se även
* klass [`Rectangle`](/slides/python-net/sv/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)