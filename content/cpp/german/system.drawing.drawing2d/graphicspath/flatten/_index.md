---
title: Flatten()
second_title: Aspose.Slides für C++ API-Referenz
description: Flacht jede Kurve im Pfad, indem sie in eine Reihe verbundener Linien umgewandelt wird. Der Flachheitswert von 0.25 wird verwendet.
type: docs
weight: 391
url: /de/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() Methode

Flacht jede Kurve im Pfad, indem sie in eine Reihe verbundener Linien umgewandelt wird. Der Flachheitswert von 0.25 wird verwendet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) Methode

Flacht jede Kurve im Pfad, indem sie in eine Reihe verbundener Linien umgewandelt wird. Der Flachheitswert von 0.25 wird verwendet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Die Transformationsmatrix, die vor dem Ebnen auf den Pfad angewendet wird |

## GraphicsPath::Flatten(const MatrixPtr\&, float) Methode

Flacht jede Kurve im Pfad, indem sie in eine Reihe verbundener Linien umgewandelt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Die Transformationsmatrix, die vor dem Ebnen auf den Pfad angewendet wird |
| flatness | **float** | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an |

## Siehe auch

* Typedef [MatrixPtr](../../matrixptr/)
* Klasse [GraphicsPath](../)
* Namensraum [System::Drawing::Drawing2D](../../)
* Bibliothek [Aspose.Slides](../../../)