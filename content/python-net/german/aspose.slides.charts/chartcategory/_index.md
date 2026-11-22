---
title: ChartCategory class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartcategory/
---
## ChartCategory Klasse

Representiert Diagrammkategorien.

Der ChartCategory-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`use_cell`](/slides/python-net/de/aspose.slides.charts/chartcategory/use_cell/) | Wenn true, dann ist die AsCell-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird zum <br/>            Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie).<br/>            Wenn false, dann ist die AsLiteral-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird NICHT zum <br/>            Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien).<br/>            Nur-Lesen **bool**. |
| [`as_cell`](/slides/python-net/de/aspose.slides.charts/chartcategory/as_cell/) | Gibt ein IChartDataCell-Objekt zurück oder legt es fest.<br/>            Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene „0“ verwendet.<br/>            Lesen/Schreiben [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/de/aspose.slides.charts/chartcategory/as_literal/) | Gibt ein AsLiteral-Objekt zurück oder legt es fest.<br/>            Lesen/Schreiben **any**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/chartcategory/value/) | Wenn UseCell true ist, dann repräsentiert diese Eigenschaft die AsCell.Value-Eigenschaft.<br/>            Wenn UseCell false ist, dann repräsentiert diese Eigenschaft die AsLiteral-Eigenschaft.<br/>            Lesen/Schreiben **any**. |
| [`grouping_levels`](/slides/python-net/de/aspose.slides.charts/chartcategory/grouping_levels/) | Verwalteter Container der Werte der Gruppierungsebenen der Diagrammkategorie.<br/>            Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene.<br/>            Die Indizierung der Gruppierungsebenen ist nullbasiert.<br/>            Nur-Lesen [`IChartCategoryLevelsManager`](/slides/python-net/de/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/de/aspose.slides.charts/chartcategory/cached_value/) | Ruft den zwischengespeicherten Wert einer Diagrammkategorie ab.<br/>            Nur-Lesen [`ICachedChartValue`](/slides/python-net/de/aspose.slides.charts/icachedchartvalue). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/chartcategory/remove/#) | Entfernt die Kategorie aus dem Diagramm. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)