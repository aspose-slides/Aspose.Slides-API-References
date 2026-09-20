---
title: show_leader_lines property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines vlastnost
Reprezentuje chování zobrazování vodicích čar popisků dat určeného grafu. 
True zobrazuje vodící čáry. False skrývá.
Číst/zapisovat **bool**.

### Poznámky

Pokud je nadřazený prvek tohoto objektu DataLabelFormat kolekcí DataLabelCollection popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota vlastnosti ShowLeaderLines pro všechny popisky dat v kolekci DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" způsobí, že všechny DataLabels[i].ShowLeaderLines jsou rovny val).

### Definice:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)