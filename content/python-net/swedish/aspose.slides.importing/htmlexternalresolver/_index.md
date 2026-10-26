---
title: HtmlExternalResolver class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver klass

Callback-objekt som används av HTML-importrutinen för att hämta refererade objekt såsom bilder.  
Att använda denna resolver kan skapa en sårbarhet när en klientlevererad HTML-fil får serverprogramvaran att hämta en lokal eller nätverksfil. Använd med försiktighet. Det rekommenderas att inte ange HtmlExternalResolver alls (endast inbäddade objekt kommer att läsas) eller att skapa en subklass som kontrollerar om den angivna uri är giltig.

HtmlExternalResolver-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/sv/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Löser den absoluta URI:n från bas- och relativa URI:er. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/sv/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mappar en URI till ett objekt som innehåller den faktiska resursen. |


### Se även
* modul [`aspose.slides.importing`](/slides/python-net/sv/aspose.slides.importing)
* bibliotek [`Aspose.Slides`](/slides/python-net)