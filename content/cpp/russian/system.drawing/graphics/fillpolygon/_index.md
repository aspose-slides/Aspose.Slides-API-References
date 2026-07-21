---
title: FillPolygon()
second_title: Aspose.Slides для C++ справка по API
description: Заполняет внутренние области указанного полигона с помощью указанной кисти.
type: docs
weight: 417
url: /ru/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) метод


Заполняет внутренние области указанного полигона с помощью указанной кисти.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/), определяющий параметры заливки |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Массив, содержащий точки, определяющие полигон |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Режим заливки |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) метод


Заполняет внутренние области указанного полигона с помощью указанной кисти.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/), определяющий параметры заливки |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Массив, содержащий точки, определяющие полигон |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Режим заливки |

## См. также

* Перечисление [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [Brush](../../brush/)
* Класс [Point](../../point/)
* Класс [Graphics](../)
* Класс [PointF](../../pointf/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)