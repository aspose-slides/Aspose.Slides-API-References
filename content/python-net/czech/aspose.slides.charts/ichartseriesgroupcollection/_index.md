---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection třída

Představuje kolekci skupin kombinovatelných sérií.

Typ IChartSeriesGroupCollection vystavuje následující členy:

Získá skupinu sérií podle indexu.

## Indexer

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |

### Poznámky

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny
            kombinovatelných typů sérií jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup
            enum.
            Také každá skupina sérií obsahuje série, které jsou vykresleny buď
            na primární ose nebo na sekundární ose (ne oba případy v jedné skupině).
            Princip seskupování sérií je tedy seskupování podle výše zmíněných typových skupin
            a podle typu vykreslení (primární/sekundární).

            2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro
            každou sérii ve skupině ("vlastnosti skupiny sérií").
            "vlastnosti skupiny sérií" ve třídě ChartSeriesGroup jsou čtení/zápis.
            Každá z "vlastnosti skupiny sérií" může mít projekci jen pro čtení ve třídě ChartSeries.

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)