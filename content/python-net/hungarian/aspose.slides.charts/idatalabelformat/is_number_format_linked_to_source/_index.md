---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source tulajdonság
Olvasás/írás **bool**.

### Megjegyzések

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the IsNumberFormatLinkedToSource property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to 
            all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

### Definíció:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)