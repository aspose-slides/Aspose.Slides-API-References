---
title: show_value property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value vlastnost
Representuje chování zobrazování procentuální hodnoty popisku dat určeného grafu. 
True zobrazí procentuální hodnotu. False pro skrytí.
Čtení/Zápis **bool**.


### Poznámky

If parent of this DataLabelFormat object is a DataLabelCollection kolekce popisků dat then this
property gets or sets the default value of the ShowValue vlastnost for the new data 
labels in the DataLabelCollection kolekce.
Set this property with value also sets this value to the ShowValue vlastnost 
for all data labels in the DataLabelCollection kolekce
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
all DataLabels[i].ShowValue is equal to val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)