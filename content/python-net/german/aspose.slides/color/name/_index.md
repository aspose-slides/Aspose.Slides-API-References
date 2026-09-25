---
title: name property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/color/name/
weight: 190
---
## Name-Eigenschaft
Liefert den Namen dieser Farbe.<br/>            Für eine benannte Farbe (eine benannte Konstante wie `Color.red`, oder eine Farbe, die mit [`from_name`](/slides/python-net/de/aspose.slides/color/from_name/) erstellt wurde) wird der .NET-Name zurückgegeben, z. B. `"Red"` oder `"LightBlue"`.<br/>            Für jede andere Farbe wird der ARGB-Wert als kleingeschriebene Hexadezimalzahl ohne führende Nullen zurückgegeben, z. B. `"ffff0000"`. `Color.empty.name` ist `"0"`.
            Nur-lesen **str**.

### Definition:
```python
@property
def name(self):
    ...
```


### Siehe auch
* Klasse [`Color`](/slides/python-net/de/aspose.slides/color)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)