---
title: show_category_name property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name vlastnost
Reprezentuje chování zobrazení názvu kategorie popisků dat konkrétního grafu.
            True pro zobrazení názvu kategorie popisků dat v grafu. False pro skrytí.
            Čtení/Zápis **bool**.


### Poznámky

Pokud je nadřazeným objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato
            vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky
            dat v kolekci DataLabelCollection.
            Nastavením této vlastnosti na hodnotu se také nastaví tato hodnota pro vlastnost ShowCategoryName
            u všech popisků dat v kolekci DataLabelCollection
            (tj. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" způsobí, že
            všechny DataLabels[i].ShowCategoryName jsou rovny val).

### Definice:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)