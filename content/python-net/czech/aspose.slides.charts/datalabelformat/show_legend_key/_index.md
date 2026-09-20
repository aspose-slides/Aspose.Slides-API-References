---
title: show_legend_key property
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key vlastnost
Representuje chování zobrazování legendy klíče datových popisků určeného grafu. 
            True pokud je legenda klíče datového popisku viditelná.
            Číst/psát **bool**.


### Poznámky

Pokud je nadřazený objekt tohoto DataLabelFormat objektu kolekce DataLabelCollection datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové datové popisky v kolekci DataLabelCollection.
            Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu do vlastnosti ShowLegendKey pro všechny datové popisky v kolekci DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" způsobí, že všechny DataLabels[i].ShowLegendKey jsou rovny val).

### Definice:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### Viz také
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)