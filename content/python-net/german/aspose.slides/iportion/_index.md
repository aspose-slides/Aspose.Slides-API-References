---
title: IPortion class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iportion/
---
## IPortion Klasse

Stellt einen Textabschnitt innerhalb eines Textabsatzes dar.

Der IPortion-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`portion_format`](/slides/python-net/de/aspose.slides/iportion/portion_format/) | Gibt das Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird.<br/>            Nur lesbar [`IPortionFormat`](/slides/python-net/de/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/de/aspose.slides/iportion/text/) | Liest oder setzt den Klartext eines Abschnitts.<br/>            Lesen/Schreiben **str**. |
| [`field`](/slides/python-net/de/aspose.slides/iportion/field/) | Gibt ein Feld dieses Abschnitts zurück.<br/>            Nur lesbar [`IField`](/slides/python-net/de/aspose.slides/ifield). |
| [`slide`](/slides/python-net/de/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/iportion/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/de/aspose.slides/iportion/add_field/#ifieldtype) | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| [`add_field(self, internal_string)`](/slides/python-net/de/aspose.slides/iportion/add_field/#str) | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| [`remove_field(self)`](/slides/python-net/de/aspose.slides/iportion/remove_field/#) | Konvertiert diesen Feldabschnitt in den einfachen Abschnitt. |
| [`get_rect(self)`](/slides/python-net/de/aspose.slides/iportion/get_rect/#) | Ermittelt die Koordinaten des Rechtecks, das den Abschnitt umschließt. Das Rechteck beinhaltet alle Zeilen des<br/>             Texts im Abschnitt, einschließlich leerer Zeilen. |
| [`get_coordinates(self)`](/slides/python-net/de/aspose.slides/iportion/get_coordinates/#) | Ermittelt die Koordinaten des Anfangs des Abschnitts. Die X-Koordinate des Punktes stellt den Abschnittsbeginn ab dem ersten Zeichen inklusive linker Seitenabstand dar. Die Y-Koordinate umfasst den oberen Seitenabstand. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)