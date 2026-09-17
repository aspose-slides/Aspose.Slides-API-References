---
title: Portion class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/portion/
---
## Portion Klasse

Stellt einen Abschnitt von Text innerhalb eines Textabsatzes dar.

Der Portion-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/portion/__init__/#) | Initialisiert eine neue Instanz der Portion Klasse. |
| [`__init__(self, str)`](/slides/python-net/de/aspose.slides/portion/__init__/#str) | Initialisiert eine neue Instanz der Portion Klasse. |
| [`__init__(self, portion)`](/slides/python-net/de/aspose.slides/portion/__init__/#portion) | Initialisiert eine neue Instanz der Portion Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`portion_format`](/slides/python-net/de/aspose.slides/portion/portion_format/) | Gibt das Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wurde.<br/>            Nur lesbar [`IPortionFormat`](/slides/python-net/de/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/de/aspose.slides/portion/text/) | Liest oder setzt den Klartext eines Abschnitts.<br/>            Lesen/Schreiben **str**. |
| [`field`](/slides/python-net/de/aspose.slides/portion/field/) | Gibt ein Feld dieses Abschnitts zurück.<br/>            Nur lesbar [`IField`](/slides/python-net/de/aspose.slides/ifield). |
| [`slide`](/slides/python-net/de/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/portion/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/de/aspose.slides/portion/add_field/#ifieldtype) | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| [`add_field(self, internal_string)`](/slides/python-net/de/aspose.slides/portion/add_field/#str) | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| [`remove_field(self)`](/slides/python-net/de/aspose.slides/portion/remove_field/#) | Konvertiert diesen Feldabschnitt in den einfachen Abschnitt. |
| [`get_rect(self)`](/slides/python-net/de/aspose.slides/portion/get_rect/#) | Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Zeilen des Textes im Abschnitt, einschließlich leerer Zeilen. |
| [`get_coordinates(self)`](/slides/python-net/de/aspose.slides/portion/get_coordinates/#) | Ermittelt die Koordinaten des Beginns des Abschnitts. Die X-Koordinate des Punktes stellt den Beginn des Abschnitts beim ersten Zeichen einschließlich des linken Seitenabstandes dar. Die Y-Koordinate beinhaltet den oberen Seitenabstand. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)