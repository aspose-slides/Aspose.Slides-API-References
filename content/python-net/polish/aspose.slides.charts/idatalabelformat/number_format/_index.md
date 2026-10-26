---
title: number_format property
second_title: Aspose.Slides dla Pythona poprzez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format właściwość
Reprezentuje ciąg formatu dla obiektu DataLabels.
            Odczyt/zapis **str**.

### Uwagi
Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, wtedy ta właściwość pobiera lub ustawia domyślną wartość NumberFormat właściwość dla nowych etykiet danych w kolekcji DataLabelCollection.
            Gdy ta właściwość jest ustawiana na wartość, ta wartość jest również ustawiana dla NumberFormat właściwość dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" powoduje, że wszystkie DataLabels[i].NumberFormat są równe val).

### Definicja:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Zobacz także
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)