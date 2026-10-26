---
title: show_label_value_from_cell property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell vlastnost
Reprezentuje chování zobrazování hodnoty buňky popisku dat určitého grafu. 
            True zobrazí hodnotu buňky. False pro skrytí.
            Čtení/zápis **bool**.


### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové popisky dat v kolekci DataLabelCollection.
            Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu vlastnosti ShowLabelValueFromCell pro všechny popisky dat v kolekci DataLabelCollection
            (tj. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" způsobí, že všechny DataLabels[i].ShowLabelValueFromCell jsou rovny val).

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
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)