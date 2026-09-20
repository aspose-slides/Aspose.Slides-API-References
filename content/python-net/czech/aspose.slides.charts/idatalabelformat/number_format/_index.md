---
title: number_format property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format vlastnost
Reprezentuje řetězec formátu pro objekt DataLabels.
Čtení/zápis **str**.

### Poznámky

Pokud je nadřazený objekt tohoto DataLabelFormat objektu kolekcí DataLabelCollection štítků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové štítky dat v kolekci DataLabelCollection.  
Když je tato vlastnost nastavena na hodnotu, je tato hodnota také nastavena pro vlastnost NumberFormat pro všechny štítky dat v kolekci DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" způsobí, že všechny DataLabels[i].NumberFormat budou mít hodnotu val).

### Definice:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)