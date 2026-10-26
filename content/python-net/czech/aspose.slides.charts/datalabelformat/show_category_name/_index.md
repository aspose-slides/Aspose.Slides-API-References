---
title: show_category_name property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name vlastnost
Representuje chování zobrazování názvu kategorie popisků dat určeného grafu.
True k zobrazení názvu kategorie popisků dat v grafu. False k skrytí.
Číst/zapisovat **bool**.

### Poznámky

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat v kolekci DataLabelCollection.
Nastavením této vlastnosti na hodnotu také nastavíte tuto hodnotu pro vlastnost ShowCategoryName pro všechny popisky dat v kolekci DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" způsobí,
že všechny DataLabels[i].ShowCategoryName jsou rovny val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)