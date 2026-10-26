---
title: show_legend_key property
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key właściwość
Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu.  
True jeśli klucz legendy etykiety danych jest widoczny.  
Odczyt/zapis **bool**.

### Uwagi

Jeśli rodzic tego obiektu DataLabelFormat jest kolekcją DataLabelCollection etykiet danych, to właściwość pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection.  
Ustawienie tej właściwości na wartość również ustawia tę wartość w właściwości ShowLegendKey dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" powoduje że wszystkie DataLabels[i].ShowLegendKey jest równe val).

### Definicja:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Zobacz także
* klasa [`DataLabelFormat`](/slides/python-net/pl/aspose.slides.charts/datalabelformat)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)