---
title: IChartCategoryCollection class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection Klasse

Stellt eine Sammlung von [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory)

Der Typ IChartCategoryCollection stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`use_cells`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/use_cells/) | Wenn true, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien).<br/>            Wenn false, wird das Arbeitsblatt NICHT zum Speichern von Werten verwendet (und dieser Fall unterstützt keine <br/>            mehrstufigen Kategorien).<br/>            Lesen/Schreiben **bool**. |
| [`grouping_level_count`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Gibt die Anzahl der verwendeten Kategorigruppierungsebenen zurück.<br/>            Ist mehr als eins für mehrstufige Kategorien.<br/>            Nur-Lesen **int**. |

Ruft das Element am angegebenen Index ab.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus <br/>            [`IChartDataCell`](/slides/python-net/de/aspose.slides.charts/ichartdatacell) erstellt und zur Sammlung hinzugefügt. |
| [`add(self, value)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/add/#any) | Erstellt ein neues [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory) aus dem Wert und fügt es der Sammlung hinzu. |
| [`index_of(self, value)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Sucht nach dem angegebenen [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Sammlung zurück. |
| [`remove(self, value)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Entfernt den angegebenen Wert. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Entfernt das Element am angegebenen Index. |
| [`clear(self)`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection/clear/#) | Entfernt alle Elemente aus der Sammlung. |

### Siehe auch
* Klasse [`IChartCategory`](/slides/python-net/de/aspose.slides.charts/ichartcategory)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)