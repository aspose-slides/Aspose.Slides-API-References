---
title: Intersect()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt das Rechteck, das vom aktuellen Objekt repräsentiert wird, durch das Rechteck, das sich aus seiner Schnittmenge mit dem durch das angegebene Objekt repräsentierten Rechteck ergibt.
type: docs
weight: 274
url: /de/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) method


Ersetzt das Rechteck, das vom aktuellen Objekt repräsentiert wird, durch das Rechteck, das sich aus seiner Schnittmenge mit dem vom angegebenen Objekt repräsentierten Rechteck ergibt.

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Das [Rectangle](../)-Objekt, das das Rechteck darstellt, mit dem das vom aktuellen Objekt repräsentierte Rechteck zu schneiden ist |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) method


Gibt ein Rechteck zurück, das das Ergebnis der Schnittmenge der angegebenen Rechtecke ist.

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const [Rectangle](../)\& | Das erste Rechteck, das geschnitten werden soll |
| b | const [Rectangle](../)\& | Das zweite Rechteck, das geschnitten werden soll |

### Rückgabewert

Das Ergebnis der Schnittmenge von **a** mit **b**

## Siehe auch

* Klasse [Rectangle](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)