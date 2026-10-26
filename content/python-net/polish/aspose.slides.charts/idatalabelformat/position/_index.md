---
title: position property
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## właściwość position
Reprezentuje pozycję etykiety danych.  
Odczyt/zapis [`LegendDataLabelPosition`](/slides/python-net/pl/aspose.slides.charts/legenddatalabelposition).

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection.  
Reprezentuje pozycję dla obiektów DataLabel.  
Ustawienie tej właściwości powoduje również ustawienie tej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.DefaultDataLabelFormat.Position = val;" powoduje, że wszystkie DataLabels[i].Position są równe val).

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
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* wyliczenie [`LegendDataLabelPosition`](/slides/python-net/pl/aspose.slides.charts/legenddatalabelposition)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)