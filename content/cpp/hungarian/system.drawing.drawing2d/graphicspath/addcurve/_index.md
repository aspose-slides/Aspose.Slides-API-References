---
title: AddCurve()
second_title: Aspose.Slides C++ API hivatkozás
description: Hozzáadja a megadott görbét az aktuális objektum által képviselt útvonalhoz.
type: docs
weight: 274
url: /hu/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) method


Hozzáadja a megadott görbét az aktuális objektum által képviselt útvonalhoz.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | A görbét meghatározó pontok |
| tension | **float** | Megadja, hogy a görbe mennyire hajlik a vezérlőpontok között |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) method


Hozzáadja a megadott görbét az aktuális objektum által képviselt útvonalhoz.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | A görbét meghatározó pontok |
| tension | **float** | Megadja, hogy a görbe mennyire hajlik a vezérlőpontok között |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) method


Hozzáadja a megadott görbét az aktuális objektum által képviselt útvonalhoz.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | A görbét meghatározó pontok |
| offset | int | A **points** pont indexe, amely a görbe kezdőpontjaként szolgál |
| number_of_segments | int | A görbe rajzolásához használt szegmensek száma |
| tension | **float** | Megadja, hogy a görbe mennyire hajlik a vezérlőpontok között |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) method


Hozzáadja a megadott görbét az aktuális objektum által képviselt útvonalhoz.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | A görbét meghatározó pontok |
| offset | int | A **points** pont indexe, amely a görbe kezdőpontjaként szolgál |
| number_of_segments | int | A görbe rajzolásához használt szegmensek száma |
| tension | **float** | Megadja, hogy a görbe mennyire hajlik a vezérlőpontok között |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [GraphicsPath](../)
* Osztály [Point](../../../system.drawing/point/)
* Névtér [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)