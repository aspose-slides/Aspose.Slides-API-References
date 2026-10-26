---
title: show_series_name property
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name właściwość
Zwraca lub ustawia wartość Boolean określającą sposób wyświetlania nazwy serii dla etykiet danych na wykresie. 
            True, aby wyświetlić nazwę serii. False, aby ukryć.
            Odczyt/zapis **bool**.


### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, wtedy ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość powoduje również ustawienie tej wartości w właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" powoduje, że wszystkie DataLabels[i].ShowSeriesName są równe val).

### Definicja:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)