---
title: position property
second_title: Aspose.Slides dla Pythona poprzez .NET Odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position właściwość
Reprezentuje pozycję position etykiety danych.
Odczyt/zapis [`LegendDataLabelPosition`](/slides/python-net/pl/aspose.slides.charts/legenddatalabelposition).

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję position dla obiektów DataLabel. Ustawienie tej właściwości na wartość powoduje również ustawienie tej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.DefaultDataLabelFormat.Position = val;" powoduje, że wszystkie DataLabels[i].Position są równe val).

### Definicja:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* enumeracja [`LegendDataLabelPosition`](/slides/python-net/pl/aspose.slides.charts/legenddatalabelposition)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)