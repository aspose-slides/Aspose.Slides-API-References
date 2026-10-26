---
title: IDataLabelCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection klass

Representerar etiketter för en serie.

IDataLabelCollection-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Returnerar standardformatet för alla dataetiketter i samlingen.<br/>            Skrivskyddad [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Representerar formatet för ledarelinjer för dataetiketter.<br/>            Skrivskyddad [`IChartLinesFormat`](/slides/python-net/sv/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/is_visible/) | False betyder att dataetiketten inte är synlig som standard (och därför är alla <br/>            Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska).<br/>            Skrivskyddad **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Hämtar antalet synliga dataetiketter i samlingen.<br/>            Skrivskyddad **int**. |
| [`count`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/count/) | Hämtar antalet alla dataetiketter i samlingen.<br/>            Skrivskyddad **int**. |
| [`parent_series`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/parent_series/) | Returnerar föräldrakartens serie.<br/>            Skrivskyddad [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Hämtar dataetiketten för datapunkten med det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`hide(self)`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/hide/#) | Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för <br/>            egenskapen DefaultDataLabelFormat till falskt läge.<br/>            IsVisible kommer att vara falskt efter detta. |
| [`index_of(self, value)`](/slides/python-net/sv/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Returnerar ett index för den angivna DataLabel i samlingen. |


### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)