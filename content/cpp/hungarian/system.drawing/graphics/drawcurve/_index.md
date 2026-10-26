---
title: DrawCurve()
second_title: Aspose.Slides C++-hoz API Referenciája
description: Spline-t rajzol a megadott tollal.
type: docs
weight: 794
url: /hu/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) metódus

Spline-t rajzol a megadott pen használatával.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen a spline rajzolásához |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) a pontok, amelyek meghatározzák a spline-t |
| tension | **float** | Az érték, amely meghatározza a spline feszültségét |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) metódus

Spline-t rajzol a megadott pen használatával.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen a spline rajzolásához |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) a pontok, amelyek meghatározzák a spline-t |
| tension | **float** | Az érték, amely meghatározza a spline feszültségét |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) metódus

Spline-t rajzol a megadott pen használatával.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen a spline rajzolásához |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) a pontok, amelyek meghatározzák a spline-t |
| offset | **int32_t** | Az **points** tömb első elemétől számított eltolás |
| numberOfSegments | **int32_t** | A görbébe belefoglalandó szegmensek száma |
| tension | **float** | Az érték, amely meghatározza a spline feszültségét |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) metódus

Spline-t rajzol a megadott pen használatával.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen a spline rajzolásához |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) a pontok, amelyek meghatározzák a spline-t |
| offset | **int32_t** | Az **points** tömb első elemétől számított eltolás |
| numberOfSegments | **int32_t** | A görbébe belefoglalandó szegmensek száma |
| tension | **float** | Az érték, amely meghatározza a spline feszültségét |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Pen](../../pen/)
* Osztály [Point](../../point/)
* Osztály [Graphics](../)
* Osztály [PointF](../../pointf/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)