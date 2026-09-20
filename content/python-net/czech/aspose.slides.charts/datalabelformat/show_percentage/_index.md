---
title: show_percentage property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage vlastnost
Zastupuje chování zobrazení procentuální hodnoty datového popisku určeného grafu. 
            True zobrazuje procentuální hodnotu. False pro skrytí.
            Čtení/Zápis **bool**.


### Poznámky

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection kolekce datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové datové popisky v kolekci DataLabelCollection.
            Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu vlastnosti ShowPercentage pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" způsobí, že všechny DataLabels[i].ShowPercentage jsou rovny val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)