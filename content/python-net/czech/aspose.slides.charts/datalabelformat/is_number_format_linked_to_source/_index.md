---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source vlastnost
Read/write **bool**.

### Poznámky

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt kolekce DataLabelCollection datových popisků, pak tato
            vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové datové 
            popisky v kolekci DataLabelCollection.
            Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti IsNumberFormatLinkedToSource 
            pro všechny datové popisky v kolekci DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" způsobí, že 
            všechny DataLabels[i].IsNumberFormatLinkedToSource jsou rovny val).

### Definice:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Viz také
* třída [`DataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)