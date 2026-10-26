---
title: StringChartValue class
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.charts/stringchartvalue/
---
## StringChartValue Klasse

Stellt den Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann:
            1) in Zelle/Zellen des Arbeitsblatts, das dem Diagramm zugeordnet ist;
            2) als Literalwert.

**Vererbung:**[`StringChartValue`](/slides/python-net/de/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/de/aspose.slides.charts/basechartvalue)

Der Typ StringChartValue stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/data_source_type/) | Gibt an, ob die Eigenschaft AsCell, AsCells, AsLiteralString oder AsLiteralDouble <br/>            in den abgeleiteten Klassen tatsächlich ist. Mit anderen Worten gibt sie den Typ <br/>            des Werts der Data-Eigenschaft an.<br/>            Lesen/Schreiben [`DataSourceType`](/slides/python-net/de/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/data/) | Gibt das Data-Objekt zurück oder legt es fest.<br/>            Lesen/Schreiben **any**. |
| [`as_cells`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/as_cells/) | Zuweisen eines Nullwertes ist nicht erlaubt.<br/>            Der zurückgegebene Wert ist immer nicht None.<br/>            Lesen/Schreiben [`IChartCellCollection`](/slides/python-net/de/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/as_literal_string/) | Gibt den Wert als Literal-String zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Setzt den Wert aus der angegebenen Zelle. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/de/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse<br/>            der Zellen im Arbeitsblatt zurück, die die String-Daten repräsentieren. Andernfalls wird<br/>            eine leere Zeichenkette zurückgegeben. |

### Siehe auch
* Klasse [`BaseChartValue`](/slides/python-net/de/aspose.slides.charts/basechartvalue)
* Klasse [`StringChartValue`](/slides/python-net/de/aspose.slides.charts/stringchartvalue)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)