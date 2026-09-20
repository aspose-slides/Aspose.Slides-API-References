---
title: show_label_value_from_cell property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell vlastnost
Reprezentuje chování zobrazení hodnoty buňky datové popisky určeného grafu. 
            True zobrazí hodnotu buňky. False pro skrytí.
            Čtení/Zápis **bool**.


### Poznámky

Pokud je nadřazený objekt DataLabelFormat součástí kolekce DataLabelCollection datových popisků, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové datové popisky v kolekci DataLabelCollection.
            Nastavením této vlastnosti na hodnotu také nastavíte tuto hodnotu pro vlastnost ShowLabelValueFromCell všech datových popisků v kolekci DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" způsobí, že všechny DataLabels[i].ShowLabelValueFromCell jsou rovny val).

### Definice:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Viz také
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)