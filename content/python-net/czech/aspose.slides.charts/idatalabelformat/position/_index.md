---
title: position property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position vlastnost
Reprezentuje polohu popisku dat.
            Číst/Zapisovat [`LegendDataLabelPosition`](/slides/python-net/cs/aspose.slides.charts/legenddatalabelposition).

### Poznámky

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection.
            Reprezentuje polohu pro objekty DataLabel.
            Nastavením této vlastnosti s hodnotou se také tato hodnota nastaví na vlastnost Position pro všechny popisky dat v kolekci DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" způsobí, že všechny DataLabels[i].Position jsou rovny val).

### Definice:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Viz také
* třída [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* enumerace [`LegendDataLabelPosition`](/slides/python-net/cs/aspose.slides.charts/legenddatalabelposition)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)