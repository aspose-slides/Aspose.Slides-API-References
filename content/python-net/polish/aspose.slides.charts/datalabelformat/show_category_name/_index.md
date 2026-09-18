---
title: show_category_name property
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name właściwość
Reprezentuje zachowanie wyświetlania nazwy kategorii etykiet danych określonego wykresu.
            True, aby wyświetlić nazwę kategorii dla etykiet danych na wykresie. False, aby ukryć.
            Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych 
            etykiet danych w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na wartość również ustawia tę wartość w właściwości ShowCategoryName
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" powoduje, że
            wszystkie DataLabels[i].ShowCategoryName są równe val).

### Definicja:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)