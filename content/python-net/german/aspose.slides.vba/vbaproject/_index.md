---
title: VbaProject class
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.vba/vbaproject/
---
## VbaProject Klasse

Stellt ein VBA-Projekt mit Präsentations-Makros dar.

Der VbaProject-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.vba/vbaproject/__init__/#) | Dieser Konstruktor erstellt ein neues VBA-Projekt von Grund auf.<br/>            Das Projekt wird in der Codepage 1252 Windows Latin 1 (ANSI) erstellt |
| [`__init__(self, data)`](/slides/python-net/de/aspose.slides.vba/vbaproject/__init__/#bytes) | Dieser Konstruktor lädt ein VBA-Projekt aus der binären Repräsentation eines OLE-Containers. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`name`](/slides/python-net/de/aspose.slides.vba/vbaproject/name/) | Gibt den Namen des VBA-Projekts zurück.<br/>            Nur lesbar **str**. |
| [`modules`](/slides/python-net/de/aspose.slides.vba/vbaproject/modules/) | Gibt die Liste aller Module zurück, die im VBA-Projekt enthalten sind.<br/>            Nur lesbar [`IVbaModuleCollection`](/slides/python-net/de/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/de/aspose.slides.vba/vbaproject/references/) | Gibt die Liste aller Referenzen zurück, die im VBA-Projekt enthalten sind.<br/>            Nur lesbar [`IVbaReferenceCollection`](/slides/python-net/de/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/de/aspose.slides.vba/vbaproject/is_password_protected/) | Gibt an, ob das VbaProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen.<br/>            Nur lesbar **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/de/aspose.slides.vba/vbaproject/to_binary/#) | Gibt die binäre Darstellung des VBA-Projekts als OLE-Container zurück |


### Siehe auch
* Modul [`aspose.slides.vba`](/slides/python-net/de/aspose.slides.vba)
* Bibliothek [`Aspose.Slides`](/slides/python-net)