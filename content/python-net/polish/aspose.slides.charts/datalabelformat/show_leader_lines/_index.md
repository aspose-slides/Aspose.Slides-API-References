---
title: show_leader_lines property
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## właściwość show_leader_lines
Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. 
            True wyświetla linie prowadzące. False ukrywa je.
            Odczyt/zapis **bool**.


### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta
            właściwość pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet
            w kolekcji DataLabelCollection.
            Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLeaderLines
            dla wszystkich etykiet danych w kolekcji DataLabelCollection
            (np. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" skutkuje
            tym, że wszystkie DataLabels[i].ShowLeaderLines są równe val).


### Definicja:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### Zobacz także
* class [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)