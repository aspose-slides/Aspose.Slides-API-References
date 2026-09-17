---
title: ChartDataCell class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdatacell/
---
## ChartDataCell Klasse

Stellt eine Zelle für Diagrammdaten dar.

Der Typ ChartDataCell stellt die folgenden Mitglieder zur Verfügung:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`row`](/slides/python-net/de/aspose.slides.charts/chartdatacell/row/) | Gibt den Index der Zeile des Arbeitsblatts zurück, in der sich die Zelle befindet.<br/>            Nur lesend **int**. |
| [`column`](/slides/python-net/de/aspose.slides.charts/chartdatacell/column/) | Gibt den Index der Spalte des Arbeitsblatts zurück, in der sich die Zelle befindet.<br/>            Nur lesend **int**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/chartdatacell/value/) | Liest den Wert einer Zelle oder setzt ihn.<br/>            Lese-/Schreibzugriff **any**. |
| [`formula`](/slides/python-net/de/aspose.slides.charts/chartdatacell/formula/) | Liest oder setzt die Formel im A1-Stil. |
| [`r1c1_formula`](/slides/python-net/de/aspose.slides.charts/chartdatacell/r1c1_formula/) | Liest oder setzt die Formel im R1C1-Stil. |
| [`chart_data_worksheet`](/slides/python-net/de/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | Liest das Arbeitsblatt.<br/>            Nur lesend [`IChartDataWorksheet`](/slides/python-net/de/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/de/aspose.slides.charts/chartdatacell/is_hidden/) | Bestimmt, ob die Zelle ausgeblendet ist.<br/>            Nur lesend **bool**. |
| [`custom_number_format`](/slides/python-net/de/aspose.slides.charts/chartdatacell/custom_number_format/) | Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben.<br/>            Wenn der Wert leer ist, wird der PresetNumberFormat-Wert verwendet.<br/>            Lese-/Schreibzugriff **str**. |
| [`preset_number_format`](/slides/python-net/de/aspose.slides.charts/chartdatacell/preset_number_format/) | Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. Der voreingestellte Wert muss in [0..22] oder [37..49] liegen.<br/>            Lese-/Schreibzugriff **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/de/aspose.slides.charts/chartdatacell/calculate/#bool) | Falls die Zelle eine Formel enthält, wird der Wert basierend auf dieser Formel aktualisiert. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)