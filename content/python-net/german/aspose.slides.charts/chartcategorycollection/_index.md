---
title: ChartCategoryCollection class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection Klasse

Stellt eine Sammlung von [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory) dar.

Der Typ ChartCategoryCollection stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`use_cells`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/use_cells/) | Wenn true, dann wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien).<br/>            Wenn false, dann wird das Arbeitsblatt NICHT zum Speichern von Werten verwendet (und dieser Fall unterstützt keine <br/>            mehrstufigen Kategorien).<br/>            Schreib/Lesen **bool**. |
| [`grouping_level_count`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Gibt die Anzahl der verwendeten Kategorien-Gruppierungsebenen zurück.<br/>            Ist mehr als eins für mehrstufige Kategorien.<br/>            Nur-Lesen **int**. |

Ruft das Element am angegebenen Index ab.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus <br/>            [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) erstellt und zur Sammlung hinzugefügt. |
| [`add(self, value)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/add/#any) | Erstellt ein neues [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory) aus dem Wert und fügt es der Sammlung hinzu. |
| [`index_of(self, value)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Sucht nach dem angegebenen [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Sammlung zurück. |
| [`remove(self, value)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Entfernt den angegebenen Wert. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Entfernt das Element am angegebenen Index. |
| [`clear(self)`](/slides/python-net/de/aspose.slides.charts/chartcategorycollection/clear/#) | Entfernt alle Elemente aus der Sammlung. |

### Siehe Auch
* Klasse [`ChartCategory`](/slides/python-net/de/aspose.slides.charts/chartcategory)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)