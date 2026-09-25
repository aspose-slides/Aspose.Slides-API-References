---
title: Rectangle class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven.
type: docs
url: /nl/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle klasse

Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven. Compatibel met .NET `System.Drawing.Rectangle`.

Het Rectangle-type biedt de volgende leden weer:

## Constructoren

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/nl/aspose.slides/rectangle/__init__/#int-int-int-int) | Maakt een rechthoek met de opgegeven locatie en grootte. Float-waarden worden afgekapt tot gehele getallen. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/nl/aspose.slides/rectangle/x/) | Geeft de x-coördinaat van de linkerbovenhoek van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`y`](/slides/python-net/nl/aspose.slides/rectangle/y/) | Geeft de y-coördinaat van de linkerbovenhoek van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`width`](/slides/python-net/nl/aspose.slides/rectangle/width/) | Geeft de breedte van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`height`](/slides/python-net/nl/aspose.slides/rectangle/height/) | Geeft de hoogte van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`left`](/slides/python-net/nl/aspose.slides/rectangle/left/) | Geeft de x-coördinaat van de linkerkant van deze rechthoek terug. Gelijk aan `x`.<br/>            Alleen-lezen **int**. |
| [`top`](/slides/python-net/nl/aspose.slides/rectangle/top/) | Geeft de y-coördinaat van de bovenkant van deze rechthoek terug. Gelijk aan `y`.<br/>            Alleen-lezen **int**. |
| [`right`](/slides/python-net/nl/aspose.slides/rectangle/right/) | Geeft de x-coördinaat die de som is van `x` en `width` van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`bottom`](/slides/python-net/nl/aspose.slides/rectangle/bottom/) | Geeft de y-coördinaat die de som is van `y` en `height` van deze rechthoek terug.<br/>            Alleen-lezen **int**. |
| [`is_empty`](/slides/python-net/nl/aspose.slides/rectangle/is_empty/) | Geeft aan of alle numerieke eigenschappen van deze rechthoek een waarde van nul hebben.<br/>            Alleen-lezen **bool**. |

## Methoden

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/nl/aspose.slides/rectangle/contains/#int-int) | Bepaalt of het opgegeven punt zich binnen deze rechthoek bevindt. |
| [`contains(self, point)`](/slides/python-net/nl/aspose.slides/rectangle/contains/#point) | Bepaalt of het opgegeven punt zich binnen deze rechthoek bevindt. |
| [`contains(self, rect)`](/slides/python-net/nl/aspose.slides/rectangle/contains/#rectangle) | Bepaalt of het rechthoekige gebied vertegenwoordigd door `rect` volledig binnen deze rechthoek zit. |


### Opmerkingen

Rechthoeken worden vergeleken op hun locatie en grootte met `==` en kunnen gebruikt worden als sleutels in een dictionary of als leden van een set.


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)