---
title: separator property
second_title: Aspose.Slides dla Pythona - referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator właściwość
Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie.
            Odczyt/zapis **str**.


### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość ustawia także tę wartość w właściwości Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.Separator = val;" powoduje, że wszystkie DataLabels[i].Separator są równe val).

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
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)