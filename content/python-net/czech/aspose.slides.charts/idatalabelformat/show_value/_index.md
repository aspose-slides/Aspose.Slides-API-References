---
title: show_value property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value vlastnost
Představuje chování zobrazování procentuální hodnoty datového štítku určeného grafu.
True zobrazí procentuální hodnotu. False pro skrytí.
Čtení/Zápis **bool**.

### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection datových štítků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové datové štítky v kolekci DataLabelCollection.
Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowValue pro všechny datové štítky v kolekci DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" způsobí, že všechny DataLabels[i].ShowValue jsou rovny val).

### Definice:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)