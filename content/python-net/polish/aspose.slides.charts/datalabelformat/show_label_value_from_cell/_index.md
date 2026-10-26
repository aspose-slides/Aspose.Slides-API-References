---
title: show_label_value_from_cell property
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell właściwość
Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. 
True wyświetla wartość komórki. False ukrywa ją.
Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji DataLabelCollection.
Ustawienie tej właściwości na określoną wartość ustawia także tę wartość w właściwości ShowLabelValueFromCell
dla wszystkich etykiet danych w kolekcji DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" powoduje,
że wszystkie DataLabels[i].ShowLabelValueFromCell jest równe val).

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
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)