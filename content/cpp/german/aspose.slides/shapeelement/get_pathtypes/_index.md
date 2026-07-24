---
title: get_PathTypes()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array von Byte-Werten zurück, das den Typ jedes Punktes im Pfad des Elements angibt.
type: docs
weight: 27
url: /de/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() Methode


Liefert ein Array von Byte-Werten, das den Typ jedes Punktes im Pfad des Elements angibt.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Hinweise


**0** Gibt an, dass der Punkt der Anfang einer Figur ist.

**1** Gibt an, dass der Punkt einer der beiden Endpunkte einer Linie ist.

**3** Gibt an, dass der Punkt ein Endpunkt oder ein Steuerpunkt einer kubischen Bezier-Spline ist.

**7** Maskiert alle Bits außer den drei niederwertigen Bits, die den Punkttyp angeben.

**16** Gibt an, dass das zugehörige Segment gestrichelt ist.

**32** Gibt an, dass der Punkt ein Marker ist.

**128** Gibt an, dass der Punkt der letzte Punkt in einem geschlossenen Teilpfad (Figur) ist.

**129** Gibt einen Datenpunkt an, der sowohl Endpunkt eines Liniensegments als auch letzter Punkt eines geschlossenen Teilpfads ist.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)