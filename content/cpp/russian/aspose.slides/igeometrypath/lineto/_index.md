---
title: LineTo()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет линию в конец пути
type: docs
weight: 79
url: /ru/aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) метод

Добавляет линию к концу пути

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | Конечная точка линии |

## IGeometryPath::LineTo(float, float) метод

Добавляет линию к концу пути

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X конечной точки линии |
| y | **float** | Координата Y конечной точки линии |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) метод

Добавляет линию в указанное место пути

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | Конечная точка |
| index | **uint32_t** | Индекс сегмента в PathData |

## IGeometryPath::LineTo(float, float, uint32_t) метод

Добавляет линию в указанное место пути

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X точки |
| y | **float** | Координата Y точки |
| index | **uint32_t** | Индекс сегмента в PathData |

## См. также

* Класс [PointF](../../../system.drawing/pointf/)
* Класс [IGeometryPath](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)