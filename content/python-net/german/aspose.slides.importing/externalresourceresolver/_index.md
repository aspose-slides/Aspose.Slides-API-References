---
title: ExternalResourceResolver class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver Klasse

Callback-Klasse, die zum Auflösen externer Ressourcen beim Import von Html- und Svg-Dokumenten verwendet wird.
            Die Verwendung dieses Resolvers kann eine Sicherheitslücke erzeugen, wenn eine vom Client bereitgestellte HTML- oder SVG-Datei die Serversoftware dazu veranlasst, lokale oder Netzwerkdateien zu erhalten. Mit Vorsicht verwenden. Es wird empfohlen, ExternalResourceResolver überhaupt nicht anzugeben (es werden nur eingebettete Objekte gelesen) oder eine Unterklasse zu erstellen, die prüft, ob die angegebene uri gültig ist.

Der Typ ExternalResourceResolver stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/de/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Löst die absolute URI aus den Basis- und relativen URIs auf. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/de/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält. |

### Siehe auch
* Modul [`aspose.slides.importing`](/slides/python-net/de/aspose.slides.importing)
* Bibliothek [`Aspose.Slides`](/slides/python-net)