---
title: ISmartArtNode class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode Klasse

Stellt einen Knoten eines SmartArt-Diagramms dar.

Der Typ ISmartArtNode stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/child_nodes/) | Gibt Sammlungen aller Kindknoten des aktuellen Knotens zurück.<br/>            Nur lesbar [`ISmartArtNodeCollection`](/slides/python-net/de/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/shapes/) | Gibt Sammlungen aller dem Knoten zugeordneten Formen zurück.<br/>            Nur lesbar [`ISmartArtShapeCollection`](/slides/python-net/de/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/text_frame/) | Gibt den Text des Knotens zurück oder setzt ihn.<br/>            Nur lesbar [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/is_assistant/) | Gibt den Knoten als Assistenten zurück oder setzt ihn.<br/>            Lesen/Schreiben **bool**. |
| [`level`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/level/) | Gibt die Verschachtelungsebene des Knotens zurück.<br/>            Nur lesbar **int**. |
| [`bullet_fill_format`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Gibt das FillFormat-Objekt zurück, das die Füllformatierungsattribute für ein Aufzählungszeichen des Knotens enthält.<br/>            Hinweis: Kann für bestimmte SmartArt-Layout-Typen, die keine Aufzählungszeichen für Knoten bereitstellen, None zurückgeben.<br/>            Nur lesbar [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/position/) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie.<br/>            Lesen/Schreiben **int**. |
| [`is_hidden`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/is_hidden/) | Gibt true zurück, wenn dieser Knoten ein versteckter Knoten im Datenmodell ist.<br/>            Nur lesbar **bool**. |
| [`organization_chart_layout`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Gibt den mit dem aktuellen Knoten verknüpften Layouttyp des Organigramms zurück oder setzt ihn.<br/>            Lesen/Schreiben [`OrganizationChartLayoutType`](/slides/python-net/de/aspose.slides.smartart/organizationchartlayouttype). |

## Methoden

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.smartart/ismartartnode/remove/#) | Entfernt den aktuellen Knoten. |

### Siehe auch
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)