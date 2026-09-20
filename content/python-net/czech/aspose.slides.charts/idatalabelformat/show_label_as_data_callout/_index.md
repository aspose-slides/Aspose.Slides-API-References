---
title: show_label_as_data_callout property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout vlastnost
Určuje, zda bude datová značka specifikovaného grafu zobrazena jako data callout nebo jako datová značka.

            Pok
            pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection datových štítků, pak tato
            vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové
            štítky v kolekci DataLabelCollection.
            Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu do vlastnosti ShowLabelAsDataCallout
            pro všechny datové štítky v kolekci DataLabelCollection
            (tj. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" způsobí, že
            všechny DataLabels[i].ShowLabelAsDataCallout jsou rovny val).

### Definice:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)