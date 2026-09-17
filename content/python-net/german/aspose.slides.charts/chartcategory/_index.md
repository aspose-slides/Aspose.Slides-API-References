---
title: ChartCategory class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartcategory/
---
## ChartCategory Klasse

Stellt Diagrammkategorien dar.

Der Typ ChartCategory stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`use_cell`](/slides/python-net/de/aspose.slides.charts/chartcategory/use_cell/) | Wenn true, dann ist die AsCell-Eigenschaft tatsächlich. Mit anderen Worten, das Arbeitsblatt wird verwendet zum <br/>            Speichern der Kategorie (dieser Fall unterstützt eine mehrstufige Kategorie).<br/>            Wenn false, dann ist die AsLiteral-Eigenschaft tatsächlich. Mit anderen Worten, das Arbeitsblatt wird NICHT verwendet <br/>            zum Speichern der Kategorie (und dieser Fall unterstützt keine mehrstufigen Kategorien).<br/>            Nur lesend **bool**. |
| [`as_cell`](/slides/python-net/de/aspose.slides.charts/chartcategory/as_cell/) | Ruft ein IChartDataCell-Objekt ab oder setzt es.<br/>            Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet.<br/>            Lesen/Schreiben [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/de/aspose.slides.charts/chartcategory/as_literal/) | Ruft ein AsLiteral-Objekt ab oder setzt es.<br/>            Lesen/Schreiben **any**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/chartcategory/value/) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar.<br/>            Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar.<br/>            Lesen/Schreiben **any**. |
| [`grouping_levels`](/slides/python-net/de/aspose.slides.charts/chartcategory/grouping_levels/) | Verwalteter Container der Werte der Diagrammkategorie-Gruppierungsebenen.<br/>            Mehrstufige Kategorie enthält mehr als eine Gruppierungsebene.<br/>            Die Indizierung der Gruppierungsebenen ist nullbasiert.<br/>            Nur lesend [`IChartCategoryLevelsManager`](/slides/python-net/de/aspose.slides.charts/ichartcategorylevelsmanager). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`remove(self)`](/slides/python-net/de/aspose.slides.charts/chartcategory/remove/#) | Entfernt die Kategorie aus dem Diagramm. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)