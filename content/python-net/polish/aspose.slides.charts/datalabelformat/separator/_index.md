---
title: separator property
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## właściwość separator
Ustawia lub zwraca obiekt Variant reprezentujący separator używany dla etykiet danych na wykresie.

Read/write **str**.

### Uwagi
Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to
właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych
etykiet danych w kolekcji DataLabelCollection.
Ustawienie tej właściwości z wartością powoduje także ustawienie tej wartości w właściwości
Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection
(np. "DataLabels.DefaultDataLabelFormat.Separator = val;" powoduje,
że wszystkie DataLabels[i].Separator są równe val).

### Definicja:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)