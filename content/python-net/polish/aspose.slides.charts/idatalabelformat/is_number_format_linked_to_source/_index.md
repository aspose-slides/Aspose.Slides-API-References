---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source właściwość
Odczyt/zapis **bool**.

### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the IsNumberFormatLinkedToSource property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to 
            all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

### Definicja:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)