---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt die Breite- und Höhenwerte des angegebenen SizeF-Objekts zu den X- und Y-Koordinatenwerten des angegebenen PointF-Objekts hinzu.
type: docs
weight: 144
url: /de/system.drawing/pointf/add/
---
## PointF::Add(const PointF&, const SizeF&) Methode


Fügt die Breite- und Höhenwerte des angegebenen [SizeF](../../sizef/)-Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](../)-Objekts hinzu.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [PointF](../)\& | Der Punkt, der verschoben werden soll |
| size | const [SizeF](../../sizef/)\& | Das [SizeF](../../sizef/)-Objekt, das die Werte angibt, die zu den Koordinatenwerten des **point** addiert werden sollen |

### Rückgabewert

Ein neues [PointF](../)-Objekt, dessen X-Koordinatenwert gleich der Summe des X-Koordinatenwerts von **point** und des Breitewerts von **size** ist und dessen Y-Koordinatenwert gleich der Summe des Y-Koordinatenwerts von **point** und des Höhenwerts von **size**.

## PointF::Add(const PointF&, const Size&) Methode


Fügt die Breite- und Höhenwerte des angegebenen [Size](../../size/)-Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](../)-Objekts hinzu.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [PointF](../)\& | Der Punkt, der verschoben werden soll |
| size | const [Size](../../size/)\& | Das [Size](../../size/)-Objekt, das die Werte angibt, die zu den Koordinatenwerten des **point** addiert werden sollen |

### Rückgabewert

Ein neues [PointF](../)-Objekt, dessen X-Koordinatenwert gleich der Summe des X-Koordinatenwerts von **point** und des Breitewerts von **size** ist und dessen Y-Koordinatenwert gleich der Summe des Y-Koordinatenwerts von **point** und des Höhenwerts von **size**.

## Siehe auch

* Klasse [PointF](../)
* Klasse [SizeF](../../sizef/)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)