---
title: HtmlExternalResolver class
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver Klasse

Callback-Objekt, das von der HTML-Importroutine verwendet wird, um referenzierte Objekte wie Bilder zu erhalten.
            Die Verwendung dieses Resolvers könnte eine Schwachstelle erzeugen, wenn eine vom Client bereitgestellte HTML-Datei die Serversoftware veranlasst, lokale oder Netzwerkdateien abzurufen. Mit Vorsicht verwenden. Es wird empfohlen, HtmlExternalResolver überhaupt nicht anzugeben (nur eingebettete Objekte werden gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene URI gültig ist.

Der Typ HtmlExternalResolver stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/de/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Löst die absolute URI aus Basis- und relativen URIs auf. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/de/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Bildet eine URI auf ein Objekt ab, das die eigentliche Ressource enthält. |


### Siehe auch
* Modul [`aspose.slides.importing`](/slides/python-net/de/aspose.slides.importing)
* Bibliothek [`Aspose.Slides`](/slides/python-net)