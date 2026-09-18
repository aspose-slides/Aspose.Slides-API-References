---
title: show_leader_lines property
second_title: Aspose.Slides dla Pythona w .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines właściwość
Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. 
True wyświetla linie prowadzące. False ukrywa je.
Odczyt/zapis **bool**.


### Uwagi

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet danych w kolekcji DataLabelCollection.  
Ustawienie tej właściwości na wartość ustawia również tę wartość w właściwości ShowLeaderLines dla wszystkich etykiet danych w kolekcji DataLabelCollection  
(np. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" powoduje, że wszystkie DataLabels[i].ShowLeaderLines są równe val).

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
* klasa [`IDataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/idatalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)