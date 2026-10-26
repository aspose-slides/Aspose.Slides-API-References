---
title: show_leader_lines property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines Eigenschaft
Stellt das Anzeigeverhalten der Führungslinien von Datenbeschriftungen eines angegebenen Diagramms dar. 
            True zeigt die Führungslinien an. False verbirgt sie.
            Lesen/Schreiben **bool**.


### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLeaderLines-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab bzw. setzt ihn.
Setzen Sie diese Eigenschaft mit einem Wert, setzt dies ebenfalls den Wert der ShowLeaderLines-Eigenschaft für alle Datenbeschriftungen in der DataLabelCollection-Sammlung (i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" bewirkt, dass alle DataLabels[i].ShowLeaderLines gleich val sind).

### Definition:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### Siehe auch
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)