---
title: show_bubble_size property
second_title: Aspose.Slides dla Pythona w .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size właściwość
Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. 
True wyświetla wartość rozmiaru bąbelka. False ukrywa.
Odczyt/zapis **bool**.

### Uwagi
Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych etykiet danych w kolekcji DataLabelCollection.
Ustawienie tej właściwości na określoną wartość ustawia także tę wartość w właściwości ShowBubbleSize dla wszystkich etykiet danych w kolekcji DataLabelCollection
(np. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" powoduje, że wszystkie DataLabels[i].ShowBubbleSize jest równe val).

### Definicja:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)