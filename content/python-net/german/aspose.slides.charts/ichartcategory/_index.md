---
title: IChartCategory class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartcategory/
---
## IChartCategory Klasse

Stellt Diagrammkategorien dar.

Der Typ IChartCategory stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`use_cell`](/slides/python-net/de/aspose.slides.charts/ichartcategory/use_cell/) | Wenn true, dann ist die AsCell-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird zum <br/>            Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie).<br/>            Wenn false, dann ist die AsLiteral-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird NICHT zum <br/>            Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien).<br/>            Schreibgeschützt **bool**. |
| [`as_cell`](/slides/python-net/de/aspose.slides.charts/ichartcategory/as_cell/) | Gibt ein IChartDataCell-Objekt zurück oder setzt es.<br/>            Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet.<br/>            Lesen/Schreiben [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/de/aspose.slides.charts/ichartcategory/as_literal/) | Gibt AsLiteral zurück oder setzt es, wenn UseCell false ist.<br/>            Lesen/Schreiben **any**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/ichartcategory/value/) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar.<br/>            Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar.<br/>            Lesen/Schreiben **any**. |
| [`cached_value`](/slides/python-net/de/aspose.slides.charts/ichartcategory/cached_value/) | Liefert den zwischengespeicherten Wert einer Diagrammkategorie.<br/>            Schreibgeschützt [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/de/aspose.slides.charts/ichartcategory/grouping_levels/) | Verwalteter Container der Werte der Gruppierungsebenen einer Diagrammkategorie.<br/>            Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene.<br/>            Die Indizierung der Gruppierungsebenen ist nullbasiert.<br/>            Schreibgeschützt [`IChartCategoryLevelsManager`](/slides/python-net/de/aspose.slides.charts/ichartcategorylevelsmanager). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/ichartcategory/remove/#) | Entfernt die Kategorie aus dem Diagramm. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)