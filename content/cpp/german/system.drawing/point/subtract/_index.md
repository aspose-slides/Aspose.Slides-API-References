---
title: Subtract()
second_title: Aspose.Slides für C++ API-Referenz
description: Subtrahiert die Breiten- und Höhenwerte des angegebenen Size-Objekts von den X- und Y-Koordinatenwerten des angegebenen Point-Objekts entsprechend.
type: docs
weight: 196
url: /de/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) Methode

Subtrahiert die Breiten- und Höhenwerte des angegebenen [Size](../../size/)-Objekts von den X- und Y-Koordinatenwerten des angegebenen [Point](../)-Objekts entsprechend.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [Point](../)\& | Der zu übersetzende Punkt |
| size | const [Size](../../size/)\& | Das [Size](../../size/)-Objekt, das die Werte angibt, die von den Koordinatenwerten des **point** subtrahiert werden sollen |

### Rückgabewert

Ein neues [Point](../)-Objekt, dessen X-Koordinatenwert dem Ergebnis der Subtraktion des Breitenwerts von **size** vom X-Koordinatenwert von **point** entspricht und dessen Y-Koordinatenwert dem Ergebnis der Subtraktion des Höhenwerts von **size** vom Y-Koordinatenwert von **point** entspricht

## Siehe auch

* Klasse [Point](../)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)