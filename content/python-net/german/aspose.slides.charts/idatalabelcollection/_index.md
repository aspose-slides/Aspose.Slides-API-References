---
title: IDataLabelCollection class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection Klasse

Stellt die Beschriftungen einer Serie dar.

Der Typ IDataLabelCollection stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück.<br/>            Nur lesbar [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Stellt das Format der Führungs-Linien der Datenbeschriftungen dar.<br/>            Nur lesbar [`IChartLinesFormat`](/slides/python-net/de/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/is_visible/) | False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und somit alle <br/>            Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind).<br/>            Nur lesbar **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Ermittelt die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung.<br/>            Nur lesbar **int**. |
| [`count`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/count/) | Ermittelt die Anzahl aller Datenbeschriftungen in der Sammlung.<br/>            Nur lesbar **int**. |
| [`parent_series`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/parent_series/) | Gibt die übergeordnete Diagrammserie zurück.<br/>            Nur lesbar [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Liefert die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`hide(self)`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/hide/#) | Macht die Datenbeschriftung standardmäßig ausgeblendet, indem alle Show*-Flags (ShowValue, ...) der <br/>            Eigenschaft DefaultDataLabelFormat auf den Zustand false gesetzt werden.<br/>            IsVisible wird danach false sein. |
| [`index_of(self, value)`](/slides/python-net/de/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Gibt den Index der angegebenen DataLabel in der Sammlung zurück. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)