---
title: show_series_name property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name vlastnost
Vrací nebo nastavuje hodnotu typu Boolean, která určuje chování zobrazování názvu řady pro popisky dat v grafu. 
True pro zobrazení názvu řady. False pro skrytí.
Read/write **bool**.

### Poznámky

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, tj. sbírka popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové popisky dat ve sbírce DataLabelCollection.  
Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowSeriesName u všech popisků dat ve sbírce DataLabelCollection  
(např. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" způsobí, že všechny DataLabels[i].ShowSeriesName jsou rovny val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)