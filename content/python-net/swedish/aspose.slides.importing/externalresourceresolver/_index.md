---
title: ExternalResourceResolver class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver klass

Callback-klass som används för att lösa externa resurser under import av Html- och Svg-dokument. Att använda denna resolver kan skapa en sårbarhet när en klient tillhandahåller en HTML- eller SVG-fil som får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte ange ExternalResourceResolver alls (endast inbäddade objekt kommer att läsas) eller att skapa en subklass som kontrollerar om den angivna uri är giltig.

Typen ExternalResourceResolver exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/sv/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/sv/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |


### Se även
* modul [`aspose.slides.importing`](/slides/python-net/sv/aspose.slides.importing)
* bibliotek [`Aspose.Slides`](/slides/python-net)