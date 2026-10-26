---
title: IChartDataCell class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell Klasse

Stellt eine Zelle für Diagrammdaten dar.

Der Typ IChartDataCell stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`row`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/row/) | Gibt den Index der Zeile des Arbeitsblatts zurück, in der sich die Zelle befindet.<br/>            Nur-Lesen **int**. |
| [`column`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/column/) | Gibt den Index der Spalte des Arbeitsblatts zurück, in der sich die Zelle befindet.<br/>            Nur-Lesen **int**. |
| [`value`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/value/) | Liest oder setzt den Wert einer Zelle.<br/>            Lesen/Schreiben **any**. |
| [`formula`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/formula/) | Liest oder setzt die Formel im A1-Stil. |
| [`r1c1_formula`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Liest oder setzt die Formel im R1C1-Stil. |
| [`chart_data_worksheet`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Liest das Arbeitsblatt.<br/>            Nur-Lesen [`IChartDataWorksheet`](/slides/python-net/de/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/is_hidden/) | Bestimmt, ob die Zelle ausgeblendet ist.<br/>            Nur-Lesen **bool**. |
| [`custom_number_format`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/custom_number_format/) | Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben. <br/>            Wenn der Wert leer ist, wird der PresetNumberFormat-Wert verwendet.<br/>            Lesen/Schreiben **str**. |
| [`preset_number_format`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/preset_number_format/) | Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. Der voreingestellte Wert muss in [0..22] oder [37..49] liegen.<br/>            Lesen/Schreiben **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/de/aspose.slides.charts/ichartdatacell/calculate/#bool) | Wenn die Zelle eine Formel enthält, wird der Wert basierend auf dieser Formel aktualisiert. |


### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)