---
title: QuadraticBezierTo()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет квадратичную кривую Безье в конец пути
type: docs
weight: 105
url: /ru/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) метод


Добавляет квадратичную кривую Безье в конец пути

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Точка направления |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Конечная точка |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) метод


Добавляет квадратичную кривую Безье в конец пути

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X-координата точки направления |
| y1 | **float** | Y-координата точки направления |
| x2 | **float** | X-координата конечной точки |
| y2 | **float** | Y-координата конечной точки |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) метод


Добавляет квадратичную кривую Безье в указанное место пути

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Точка направления |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Конечная точка |
| index | **uint32_t** | Индекс сегмента в PathData |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) метод


Добавляет квадратичную кривую Безье в указанное место пути

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X-координата точки направления |
| y1 | **float** | Y-координата точки направления |
| x2 | **float** | X-координата конечной точки |
| y2 | **float** | Y-координата конечной точки |
| index | **uint32_t** | Индекс сегмента в PathData |

## См. также

* Класс [PointF](../../../system.drawing/pointf/)
* Класс [IGeometryPath](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)