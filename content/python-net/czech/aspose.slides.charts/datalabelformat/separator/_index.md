---
title: separator property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## vlastnost Separator
Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu.
            Čtení/zápis **str**.


### Poznámky

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, sbírka datových popisků, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti Separator pro nové datové popisky v kolekci DataLabelCollection.
            Nastavením této vlastnosti s hodnotou také nastavíte tuto hodnotu do vlastnosti Separator pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.DefaultDataLabelFormat.Separator = val;" způsobí, že všechny DataLabels[i].Separator jsou rovny val).

### Definice:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Viz také
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)