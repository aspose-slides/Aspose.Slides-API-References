---
title: show_legend_key property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key vlastnost
Reprezentuje chování zobrazení legendy klíče datových popisků určeného grafu. 
            True pokud je legenda klíče datového popisku viditelná.
            Číst/zapisovat **bool**.

### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection datových popisků, pak tato
            vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowLegendKey pro nové datové
            popisky v kolekci DataLabelCollection.
            Nastavením této vlastnosti na hodnotu také nastavíte tuto hodnotu pro vlastnost ShowLegendKey
            u všech datových popisků v kolekci DataLabelCollection
            (tj. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" způsobí, že
            všechny DataLabels[i].ShowLegendKey jsou rovny val).

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
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)