---
title: DataLabelCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection klass

Representerar en serieetiketter.

DataLabelCollection-typen exponerar följande medlemmar:

## Egenskaper

| Egendom | Beskrivning |
| :- | :- |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/chart/) | Returnerar den överordnade chart.<br/>            Skrivskyddad [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/is_visible/) | Falskt betyder att dataetikett inte är synlig som standard (och så är alla <br/>            Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska).<br/>            Skrivskyddad **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Hämtar antalet synliga dataetiketter i samlingen.<br/>            Skrivskyddad **int**. |
| [`count`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/count/) | Hämtar antalet alla dataetiketter i samlingen.<br/>            Skrivskyddad **int**. |
| [`default_data_label_format`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Hämtar standardformatet för dataetikett.<br/>            Skrivskyddad [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Representerar formatet för ledarlinjer för dataetiketter.<br/>             Skrivskyddad [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/parent_series/) | Hämtar den överordnade serien.<br/>            Skrivskyddad [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Hämtar eller anger standardformen för dataetiketter.<br/>             Returnerar [`ShapeType.NOT_DEFINED`](/slides/python-net/sv/aspose.slides/shapetype/NOT_DEFINED) om ingen form är definierad. |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/presentation/) |  |

Hämtar dataetiketten för datapunkten med det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`hide(self)`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/hide/#) | Gör dataetiketts dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för <br/>            egenskapen DefaultDataLabelFormat till falskt läge.<br/>            IsVisible kommer att vara falskt efter detta. |
| [`index_of(self, value)`](/slides/python-net/sv/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Returnerar ett index för den angivna DataLabel i samlingen. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)