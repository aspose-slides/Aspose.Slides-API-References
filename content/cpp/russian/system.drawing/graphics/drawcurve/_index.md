---
title: DrawCurve()
second_title: Справка API Aspose.Slides для C++
description: Рисует сплайн с использованием указанного пера.
type: docs
weight: 794
url: /ru/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) метод

Рисует сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | **float** | Значение, определяющее натяжение сплайна |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) метод

Рисует сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | **float** | Значение, определяющее натяжение сплайна |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) метод

Рисует сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| offset | **int32_t** | Смещение от первого элемента массива **points** |
| numberOfSegments | **int32_t** | Количество сегментов, включаемых в кривую |
| tension | **float** | Значение, определяющее натяжение сплайна |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) метод

Рисует сплайн с использованием указанного пера.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | pen, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| offset | **int32_t** | Смещение от первого элемента массива **points** |
| numberOfSegments | **int32_t** | Количество сегментов, включаемых в кривую |
| tension | **float** | Значение, определяющее натяжение сплайна |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)