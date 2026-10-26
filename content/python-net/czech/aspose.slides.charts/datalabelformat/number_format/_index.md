---
title: number_format property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format vlastnost
Představuje řetězec formátu pro objekt DataLabels.
Čtení/zápis **str**.

### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection.
Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat pro všechny popisky dat v kolekci DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" způsobí, že všechny DataLabels[i].NumberFormat budou mít hodnotu val).

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
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)