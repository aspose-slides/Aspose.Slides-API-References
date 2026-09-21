---
title: ExternalResourceResolver class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver klasse

Callback-klasse die wordt gebruikt om externe bronnen te resolven tijdens het importeren van Html- en Svg-documenten.
Het gebruik van deze resolver kan een kwetsbaarheid creëren wanneer een door de client verstrekt HTML- of SVG-bestand de serversoftware in staat stelt een lokaal of netwerkbestand te verkrijgen. Gebruik met voorzichtigheid. Het wordt aanbevolen om ExternalResourceResolver helemaal niet op te geven (alleen ingesloten objecten worden gelezen) of een subklasse te maken die controleert of de opgegeven URI geldig is.

Het type ExternalResourceResolver exposeert de volgende leden:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/nl/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Lost de absolute URI op vanuit de basis- en relatieve URI's. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/nl/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mapt een URI naar een object dat de daadwerkelijke bron bevat. |

### Zie ook
* module [`aspose.slides.importing`](/slides/python-net/nl/aspose.slides.importing)
* bibliotheek [`Aspose.Slides`](/slides/python-net)