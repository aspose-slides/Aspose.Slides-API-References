---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection Klasse

Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folien dar.  
Erweitert die LayoutSlideCollection Klasse mit Methoden zum Hinzufügen/Einf ügen/Entfernen/Klonen/Neuordnen von Layout-Folien im Kontext der einzelnen Sammlungen von Master's Layout-Folien.

**Vererbung:**[`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/de/aspose.slides/layoutslidecollection)

Der MasterLayoutSlideCollection-Typ stellt die folgenden Member bereit:

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Methoden

| Method | Beschreibung |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Gibt die erste Layout-Folie des angegebenen Typs zurück.<br/>Ein Typ von Layout-Folien, der gesucht wird.[`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide) mit angegebenem Typ oder None, wenn keine Layouts gefunden wurden. |
| [`remove(self, value)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Entfernt ein Layout aus der Sammlung. |
| [`remove_unused(self)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Entfernt ungenutzte Layout-Folien (Layout-Folien, deren HasDependingSlides false ist). |
| [`add_clone(self, source_layout)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position der Sammlung ein. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Fügt eine neue Layout-Folie am Ende der Sammlung hinzu. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Verschiebt die Layout-Folie von der Sammlung zur angegebenen Position. |

### Siehe auch
* Klasse [`LayoutSlideCollection`](/slides/python-net/de/aspose.slides/layoutslidecollection)
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)