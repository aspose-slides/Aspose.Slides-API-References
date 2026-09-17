---
title: IStringChartValue class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue Klasse

Stellt einen Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann:
            1) in Zelle(n) einer Arbeitsmappe, die mit dem Diagramm verknüpft ist;
            2) als Literalwert.

Der Typ IStringChartValue stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`as_literal_string`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/as_literal_string/) | Gibt die Literalzeichenkette zurück oder setzt sie, wenn die DataSourceType-Eigenschaft DataSourceType.StringLiterals ist.<br/>            Lesen/Schreiben **str**. |
| [`as_cells`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/data/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`to_string(self)`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/to_string/#) | Gibt die Zeichenkettenrepräsentation zurück. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Setzt den Wert aus der angegebenen Zelle. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/de/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Wenn die DataSourceType-Eigenschaft DataSourceType.Worksheet ist, gibt diese Methode die Adresse<br/>            der Zellen in der Arbeitsmappe zurück, die die Zeichenkettendaten darstellen. Andernfalls wird<br/>            eine leere Zeichenkette zurückgegeben. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)