---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides dla Pythona przez .NET API Referencja
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source właściwość
Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection.
Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości IsNumberFormatLinkedToSource dla wszystkich etykiet danych w kolekcji DataLabelCollection
(np. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" powoduje, że wszystkie DataLabels[i].IsNumberFormatLinkedToSource są równe val).

### Definicja:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)