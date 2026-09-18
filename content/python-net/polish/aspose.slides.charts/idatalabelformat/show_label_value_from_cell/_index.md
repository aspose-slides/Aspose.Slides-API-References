---
title: show_label_value_from_cell property
second_title: Aspose.Slides dla Pythona przez .NET API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell właściwość
Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. 
True wyświetla wartość komórki. False ukrywa.
Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych
            etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość powoduje także ustawienie tej wartości w właściwości ShowLabelValueFromCell
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" powoduje, że
            wszystkie DataLabels[i].ShowLabelValueFromCell są równe val).

### Definicja:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)