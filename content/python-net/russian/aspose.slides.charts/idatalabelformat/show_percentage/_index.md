---
title: show_percentage property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage свойство
Represents a specified chart's data label percentage value display behavior. 
True displays the percentage value. False to hide.
Чтение/запись **bool**.

### Замечания

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
property gets or sets the default value of the ShowPercentage property for the new data 
labels in the DataLabelCollection collection.
Set this property with value also sets this value to the ShowPercentage property 
for all data labels in the DataLabelCollection collection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" cause to 
all DataLabels[i].ShowPercentage is equal to val).

### Определение:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)