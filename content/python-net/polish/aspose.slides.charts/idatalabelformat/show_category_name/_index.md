---
title: show_category_name property
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name właściwość
Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu.
            True to display the category name for the data labels on a chart. False to hide.
            Odczyt/zapis **bool**.


### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).

### Definicja:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)