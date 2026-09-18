---
title: show_percentage property
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage właściwość
Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. 
            True wyświetla wartość procentową. False ukrywa ją.
            Odczyt/zapis **bool**.


### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowPercentage dla nowych
            etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość również ustawia tę wartość w właściwości ShowPercentage 
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" powoduje, że
            wszystkie DataLabels[i].ShowPercentage są równe val).

### Definicja:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)