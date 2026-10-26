---
title: HtmlExternalResolver class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver klasse

Callback-object dat door de HTML-importroutine wordt gebruikt om verwezen objecten zoals afbeeldingen te verkrijgen. Het gebruik van deze resolver kan een kwetsbaarheid veroorzaken wanneer een door de client geleverd HTML-bestand de serversoftware toestaat om lokale of netwerklocaties te benaderen. Gebruik dit met voorzichtigheid. Het wordt aanbevolen om HtmlExternalResolver helemaal niet op te geven (alleen ingesloten objecten worden gelezen) of een subclass te maken die controleert of de opgegeven uri geldig is.

Het type HtmlExternalResolver exposeert de volgende leden:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/nl/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Lost de absolute URI op basis van de basis- en relatieve URI's. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/nl/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mapt een URI naar een object dat de feitelijke bron bevat. |


### Zie ook
* module [`aspose.slides.importing`](/slides/python-net/nl/aspose.slides.importing)
* bibliotheek [`Aspose.Slides`](/slides/python-net)