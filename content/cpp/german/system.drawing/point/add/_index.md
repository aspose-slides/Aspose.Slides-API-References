---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt die Breiten- und Höhenwerte des angegebenen Size-Objekts zu den X- und Y-Koordinatenwerten des angegebenen Point-Objekts hinzu.
type: docs
weight: 183
url: /de/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) Methode


Fügt die Breite- und Höhenwerte des angegebenen [Size](../../size/)-Objekts zu den X- und Y-Koordinatenwerten des angegebenen [Point](../)-Objekts hinzu.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [Point](../)\& | Der point, der zu übersetzen ist |
| size | const [Size](../../size/)\& | Das [Size](../../size/)-Objekt, das die Werte spezifiziert, die zu den Koordinatenwerten des **point** hinzugefügt werden |

### Rückgabewert

Ein neues [Point](../)-Objekt, dessen X-Koordinatenwert gleich der Summe des X-Koordinatenwerts des **point** und des Breitewerts des **size** ist und dessen Y-Koordinatenwert gleich der Summe des Y-Koordinatenwerts des **point** und des Höhenwerts des **size** ist

## Siehe auch

* Klasse [Point](../)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)