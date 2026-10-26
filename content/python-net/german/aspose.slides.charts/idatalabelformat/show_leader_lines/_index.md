---
title: show_leader_lines property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines Eigenschaft
Stellt das Anzeigeverhalten der Leader-Linien von Datenbeschriftungen eines bestimmten Diagramms dar. 
True zeigt die Leader-Linien an. False verbirgt sie.
Lese/Schreib **bool**.

### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLeaderLines-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab bzw. setzt ihn.
Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowLeaderLines-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt.
(z. B. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" bewirkt, dass alle DataLabels[i].ShowLeaderLines den Wert val erhalten.)

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
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)