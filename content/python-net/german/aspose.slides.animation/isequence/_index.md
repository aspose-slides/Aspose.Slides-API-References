---
title: ISequence class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.animation/isequence/
---
## ISequence class

Stellt eine Sequenz (Sammlung von Effekten) dar.

Der Typ ISequence stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`count`](/slides/python-net/de/aspose.slides.animation/isequence/count/) | Gibt die Anzahl der Effekte in einer Sequenz zurück.<br/>            Nur-Lesen **int**. |
| [`trigger_shape`](/slides/python-net/de/aspose.slides.animation/isequence/trigger_shape/) | Gibt das Zielobjekt für die INTERACTIVE-Sequenz zurück oder setzt es.<br/>            Wenn die Sequenz nicht interaktiv ist, wird None zurückgegeben.<br/>            Lese/Schreib [`IShape`](/slides/python-net/de/aspose.slides/ishape). |

Gibt einen Effekt am angegebenen Index zurück.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.animation/isequence/__getitem__/) | Index |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/de/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Fügt einen neuen Effekt am Ende der Sequenz hinzu. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/de/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Fügt einen neuen Animierungseffekt für einen Absatz am Ende der Sequenz hinzu. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/de/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Fügt den neuen Diagramm-Animierungseffekt für eine Kategorie oder Serie am Ende der Sequenz hinzu. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/de/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Fügt den neuen Diagramm-Animierungseffekt für Elemente in einer Kategorie oder Serie am Ende der Sequenz hinzu. |
| [`remove(self, item)`](/slides/python-net/de/aspose.slides.animation/isequence/remove/#ieffect) | Entfernt den angegebenen Effekt aus einer Sammlung. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides.animation/isequence/remove_at/#int) | Entfernt einen Effekt aus einer Sammlung. |
| [`clear(self)`](/slides/python-net/de/aspose.slides.animation/isequence/clear/#) | Entfernt alle Effekte aus einer Sammlung. |
| [`remove_by_shape(self, shape)`](/slides/python-net/de/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Entfernt den Effekt für das angegebene Shape. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/de/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Gibt ein Array von Effekten für das angegebene Shape zurück. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/de/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Gibt ein Array von Effekten für den angegebenen Absatz zurück. |
| [`get_count(self, shape)`](/slides/python-net/de/aspose.slides.animation/isequence/get_count/#ishape) | Gibt die Anzahl der Effekte für das angegebene Shape zurück. |


### Siehe auch
* Modul [`aspose.slides.animation`](/slides/python-net/de/aspose.slides.animation)
* Bibliothek [`Aspose.Slides`](/slides/python-net)