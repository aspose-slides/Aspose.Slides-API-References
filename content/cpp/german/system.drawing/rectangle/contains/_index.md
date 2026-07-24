---
title: Contains()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der angegebene Punkt innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird.
type: docs
weight: 248
url: /de/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const Methode

Bestimmt, ob der angegebene Punkt innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die X-Koordinate des zu prüfenden Punktes |
| y | int | Die Y-Koordinate des zu prüfenden Punktes |

### Rückgabewert

True, wenn der angegebene Punkt innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird, ansonsten - false

## Rectangle::Contains(const Point\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Ein zu prüfender Punkt |

### Rückgabewert

True, wenn der angegebene Punkt innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird, ansonsten - false

## Rectangle::Contains(const Rectangle\&) const Methode

Bestimmt, ob das angegebene Rechteck innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Ein zu prüfendes Rechteck |

### Rückgabewert

True, wenn das angegebene Rechteck innerhalb des Rechtecks liegt, das vom aktuellen Objekt dargestellt wird, ansonsten - false

## Siehe auch

* Klasse [Rectangle](../)
* Klasse [Point](../../point/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)