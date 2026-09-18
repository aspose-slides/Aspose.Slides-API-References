---
title: show_value property
second_title: Aspose.Slides dla Pythona via .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value właściwość
Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. 
            True wyświetla wartość procentową. False ukrywa ją.
            Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych 
            w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość ustawia również tę wartość w właściwości ShowValue 
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" powoduje, że 
            wszystkie DataLabels[i].ShowValue są równe val).

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
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)