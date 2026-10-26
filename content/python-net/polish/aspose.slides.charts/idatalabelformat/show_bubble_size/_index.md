---
title: show_bubble_size property
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size właściwość
Represents a specified chart's data label bubble size value display behavior. 
            True wyświetla wartość rozmiaru bąbelka. False ukrywa.
            Odczyt/zapis **bool**.


### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych danych 
            etykiet w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość powoduje również ustawienie tej wartości w właściwości ShowBubbleSize 
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" powoduje, że 
            wszystkie DataLabels[i].ShowBubbleSize są równe val).

### Definicja:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)