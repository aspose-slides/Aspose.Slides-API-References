---
title: Subtract()
second_title: Aspose.Slides für C++ API-Referenz
description: Subtrahiert die Breite- und Höhenwerte des angegebenen SizeF-Objekts von den X- und Y-Koordinatenwerten des angegebenen PointF-Objekts entsprechend.
type: docs
weight: 157
url: /de/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) Methode

Subtrahiert die Breite- und Höhenwerte des angegebenen [SizeF](../../sizef/)-Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](../)-Objekts entsprechend.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Der Punkt, der verschoben werden soll |
| size | const [SizeF](../../sizef/)\& | Das [SizeF](../../sizef/)-Objekt, das die Werte angibt, die von den Koordinatenwerten des **point** subtrahiert werden sollen |

### Rückgabewert

Ein neues [PointF](../)-Objekt, dessen X-Koordinatenwert dem Ergebnis der Subtraktion des Breitenwerts von **size** vom X-Koordinatenwert von **point** entspricht und dessen Y-Koordinatenwert dem Ergebnis der Subtraktion des Höhenwerts von **size** vom Y-Koordinatenwert von **point** entspricht.

## PointF::Subtract(const PointF\&, const Size\&) Methode

Subtrahiert die Breite- und Höhenwerte des angegebenen [Size](../../size/)-Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](../)-Objekts entsprechend.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Der Punkt, der verschoben werden soll |
| size | const [Size](../../size/)\& | Das [Size](../../size/)-Objekt, das die Werte angibt, die von den Koordinatenwerten des **point** subtrahiert werden sollen |

### Rückgabewert

Ein neues [PointF](../)-Objekt, dessen X-Koordinatenwert dem Ergebnis der Subtraktion des Breitenwerts von **size** vom X-Koordinatenwert von **point** entspricht und dessen Y-Koordinatenwert dem Ergebnis der Subtraktion des Höhenwerts von **size** vom Y-Koordinatenwert von **point** entspricht.

## Siehe auch

* Klasse [PointF](../)
* Klasse [SizeF](../../sizef/)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)