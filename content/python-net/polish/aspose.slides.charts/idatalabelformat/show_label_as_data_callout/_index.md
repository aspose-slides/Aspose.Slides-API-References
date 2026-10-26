---
title: show_label_as_data_callout property
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout właściwość
Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako odwołanie danych lub jako etykieta danych.

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection.

Ustawienie tej właściwości na wartość powoduje również ustawienie tej wartości w właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" powoduje, że wszystkie DataLabels[i].ShowLabelAsDataCallout są równe val).

### Definicja:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)