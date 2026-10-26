---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source property
Read/write **bool**.

### Remarks

Pokud je rodič tohoto objektu DataLabelFormat kolekcí DataLabelCollection obsahující datové popisky, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové datové popisky v kolekci DataLabelCollection.  
Nastavením této vlastnosti na hodnotu se také nastaví tato hodnota vlastnosti IsNumberFormatLinkedToSource pro všechny datové popisky v kolekci DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

### Definition:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### See Also
* class [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)