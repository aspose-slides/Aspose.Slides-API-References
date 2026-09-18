---
title: show_value property
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value właściwość
Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. 
            True wyświetla wartość procentową. False ukrywa.
            Odczyt/zapis **bool**.


### Uwagi

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość ustawia również tę wartość w właściwości ShowValue dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" powoduje, że wszystkie DataLabels[i].ShowValue są równe val).


### Definicja:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)