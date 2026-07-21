---
title: AddCurve()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет указанный изгиб к пути, представленному текущим объектом.
type: docs
weight: 274
url: /ru/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) метод

Добавляет указанный изгиб к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Точки, задающие изгиб |
| tension | **float** | Указывает величину изгиба между контрольными точками |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) метод

Добавляет указанный изгиб к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Точки, задающие изгиб |
| tension | **float** | Указывает величину изгиба между контрольными точками |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) метод

Добавляет указанный изгиб к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Точки, задающие изгиб |
| offset | int | Индекс точки в **points**, используемый в качестве начальной точки изгиба |
| number_of_segments | int | Количество сегментов, используемых для построения изгиба |
| tension | **float** | Указывает величину изгиба между контрольными точками |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) метод

Добавляет указанный изгиб к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Точки, задающие изгиб |
| offset | int | Индекс точки в **points**, используемый в качестве начальной точки изгиба |
| number_of_segments | int | Количество сегментов, используемых для построения изгиба |
| tension | **float** | Указывает величину изгиба между контрольными точками |

## Смотрите также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [GraphicsPath](../)
* Класс [Point](../../../system.drawing/point/)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)