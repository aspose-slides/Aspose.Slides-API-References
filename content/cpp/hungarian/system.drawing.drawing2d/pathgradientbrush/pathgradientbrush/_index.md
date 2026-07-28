---
title: PathGradientBrush()
second_title: Aspose.Slides C++ API referenciája
description: Új példányt hoz létre a PathGradientBrush osztályból.
type: docs
weight: 1
url: /hu/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) konstruktor


Új példányt hoz létre a [PathGradientBrush](../) osztályból.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Egy tömb, amely a útvonal csúcspontjait tartalmazza |
| wrapMode | [WrapMode](../../wrapmode/) | Megadja, hogy a létrehozott objektum által reprezentált ecsettel rajzolt kitöltések hogyan legyenek csempézve |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) konstruktor


Új példányt hoz létre a [PathGradientBrush](../) osztályból.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Egy tömb, amely a útvonal csúcspontjait tartalmazza |
| wrapMode | [WrapMode](../../wrapmode/) | Megadja, hogy a létrehozott objektum által reprezentált ecsettel rajzolt kitöltések hogyan legyenek csempézve |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) konstruktor


Új példányt hoz létre a [PathGradientBrush](../) osztályból.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Egy [GraphicsPath](../../graphicspath/) objektum, amely meghatározza a létrehozott objektum által kitöltött útvonalat |

## Lásd még

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [PathGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)