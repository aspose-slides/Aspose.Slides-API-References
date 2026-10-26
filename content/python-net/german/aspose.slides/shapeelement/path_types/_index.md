---
title: path_types property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types Eigenschaft
Gibt ein Array von Byte-Werten zurück, das den Typ jedes Punktes im Pfad des Elements angibt.
            
**0**  Gibt an, dass der Punkt der Anfang einer Figur ist.


**1**  Gibt an, dass der Punkt einer der beiden Endpunkte einer Linie ist.


**3**  Gibt an, dass der Punkt ein Endpunkt oder Steuerpunkt einer kubischen Bézier-Kurve ist.


**7**  Maskiert alle Bits außer den drei niederwertigen Bits, die den Punkttyp anzeigen.


**16**  Gibt an, dass das entsprechende Segment gestrichelt ist.


**32**  Gibt an, dass der Punkt ein Marker ist.


**128**  Gibt an, dass der Punkt der letzte Punkt in einem geschlossenen Unterpfad (Figur) ist.


**129**  Gibt an, dass es sich um einen Datenpunkt handelt, der sowohl ein Endpunkt eines Liniensegments als auch der letzte Punkt eines geschlossenen Unterpfads ist.

### Definition:
```python
@property
def path_types(self):
    ...
```


### Siehe auch
* Klasse [`ShapeElement`](/slides/python-net/de/aspose.slides/shapeelement)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)