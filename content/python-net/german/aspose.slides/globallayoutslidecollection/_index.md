---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection Klasse

Stellt eine Sammlung aller Layout-Folien in der Präsentation dar.
            Erweitert die LayoutSlideCollection Klasse um Methoden zum Hinzufügen/Klonen von Layout-Folien im Kontext der Vereinigung der einzelnen Sammlungen der Master-Layout-Folien.

**Vererbung:**[`GlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/de/aspose.slides/layoutslidecollection)

Der Typ GlobalLayoutSlideCollection stellt die folgenden Mitglieder bereit:

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Fügt der Präsentation eine Kopie einer angegebenen Layout-Folie hinzu. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Fügt der Präsentation eine Kopie einer angegebenen Layout-Folie hinzu. |
| [`get_by_type(self, type)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Gibt die erste Layout-Folie des angegebenen Typs zurück.<br/>            Ein Typ der zu findenden Layout-Folie.[`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide) mit angegebenem Typ oder None, wenn keine Layouts gefunden wurden. |
| [`remove(self, value)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Entfernt ein Layout aus der Sammlung. |
| [`remove_unused(self)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/remove_unused/#) | Entfernt ungenutzte Layout-Folien (Layout-Folien, deren HasDependingSlides false ist). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/de/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Fügt der Präsentation eine neue Layout-Folie hinzu. |


### Siehe auch
* Klasse [`GlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/globallayoutslidecollection)
* Klasse [`LayoutSlideCollection`](/slides/python-net/de/aspose.slides/layoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)