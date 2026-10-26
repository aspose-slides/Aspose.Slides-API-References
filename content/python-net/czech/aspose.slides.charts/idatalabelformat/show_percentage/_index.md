---
title: show_percentage property
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage vlastnost
Reprezentuje chování zobrazení hodnoty procenta popisku dat specifikovaného grafu. 
True zobrazí hodnotu procenta. False pro skrytí.
Číst/zapisovat **bool**.


### Poznámky

Pokud je nadřazeným prvkem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowPercentage pro nové popisky dat v kolekci DataLabelCollection.
Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowPercentage u všech popisků dat v kolekci DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" způsobí, že všechny DataLabels[i].ShowPercentage jsou rovny val).

### Definice:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)