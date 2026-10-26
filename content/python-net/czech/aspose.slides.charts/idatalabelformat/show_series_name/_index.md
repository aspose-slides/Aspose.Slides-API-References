---
title: show_series_name property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name vlastnost
Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro popisky dat v grafu. 
            True pro zobrazení názvu řady. False pro skrytí.
            Čtení/zápis **bool**.


### Poznámky

            Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové datové popisky v kolekci DataLabelCollection.
            Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu do vlastnosti ShowSeriesName pro všechny datové popisky v kolekci DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" způsobí, že všechny DataLabels[i].ShowSeriesName jsou rovny val).


### Definice:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)