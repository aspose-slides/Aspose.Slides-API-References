---
title: Flatten()
second_title: Aspose.Slides C++ API referencia
description: Lapítja az útvonal minden görbéjét úgy, hogy azokat egy sor összekapcsolt vonallá alakítja. A 0.25-ös flatness érték kerül használatra.
type: docs
weight: 391
url: /hu/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() metódus


Minden görbét a útvonalban laposra konvertál, úgy, hogy azokat egy sor összekapcsolt vonallá alakítja. A 0.25-ös flatness érték kerül alkalmazásra.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) metódus


Minden görbét a útvonalban laposra konvertál, úgy, hogy azokat egy sor összekapcsolt vonallá alakítja. A 0.25-ös flatness érték kerül alkalmazásra.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | A transzformációs mátrix, amelyet a laposítás előtt az útvonalra kell alkalmazni |

## GraphicsPath::Flatten(const MatrixPtr\&, float) metódus


Minden görbét a útvonalban laposra konvertál, úgy, hogy azokat egy sor összekapcsolt vonallá alakítja.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | A transzformációs mátrix, amelyet a laposítás előtt az útvonalra kell alkalmazni |
| flatness | **float** | Meghatározza a megengedett legnagyobb hibát a görbe és a laposított közelítése között |

## Lásd még

* Typedef [MatrixPtr](../../matrixptr/)
* Osztály [GraphicsPath](../)
* Névtér [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)