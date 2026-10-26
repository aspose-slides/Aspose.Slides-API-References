---
title: show_leader_lines property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines vlastnost
Zastupuje chování zobrazení linií popisků dat určeného grafu.  
True zobrazuje linie popisků. False je skryje.  
Číst/Zapsat **bool**.

### Poznámky
Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat v kolekci DataLabelCollection.  
Nastavením této vlastnosti s hodnotou se také tato hodnota nastaví pro vlastnost ShowLeaderLines všech popisků dat v kolekci DataLabelCollection  
(tj. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" způsobí, že  
všechny DataLabels[i].ShowLeaderLines jsou rovny val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)