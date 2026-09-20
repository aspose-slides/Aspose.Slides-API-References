---
title: show_bubble_size property
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size vlastnost
Representuje chování zobrazování hodnoty velikosti bubliny popisku dat v určeném grafu. 
            True zobrazuje hodnotu velikosti bubliny. False pro skrytí.
            Čtení/zápis **bool**.

### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato
            vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové popisky
            v kolekci DataLabelCollection.
            Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowBubbleSize
            pro všechny popisky v kolekci DataLabelCollection
            (tj. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" způsobí, že
            všechny DataLabels[i].ShowBubbleSize jsou rovny val).

### Definice:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Viz také
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)