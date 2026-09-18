---
title: show_series_name property
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name property
Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. 
            True aby pokazać nazwę serii. False aby ukryć.
            Odczyt/zapis **bool**.


### Remarks

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych 
            etykiet w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość powoduje również ustawienie tej samej wartości w 
            właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" powoduje, że 
            wszystkie DataLabels[i].ShowSeriesName są równe val).

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### See Also
* class [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)