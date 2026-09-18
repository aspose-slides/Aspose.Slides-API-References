---
title: number_format property
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format właściwość
Reprezentuje ciąg formatowania dla obiektu DataLabels.
Odczyt/zapis **str**.

### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection.
When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### Definicja:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)