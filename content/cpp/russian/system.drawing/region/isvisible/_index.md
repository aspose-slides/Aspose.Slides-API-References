---
title: IsVisible()
second_title: Aspose.Slides для C++ справка по API
description: Определяет, содержится ли указанный пункт в области, представляемой текущим объектом.
type: docs
weight: 196
url: /ru/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Точка для проверки |

## Region::IsVisible(const PointF\&) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Точка для проверки |

## Region::IsVisible(const Rectangle\&) метод

Определяет, содержится ли любая часть указанного прямоугольника в области, представленной текущим объектом.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник для проверки |

## Region::IsVisible(const RectangleF\&) метод

Определяет, содержится ли любая часть указанного прямоугольника в области, представленной текущим объектом.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник для проверки |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом, используя указанные графические объекты.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Точка для проверки |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Контекст графики |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом, используя указанные графические объекты.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Точка для проверки |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Контекст графики |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) метод

Определяет, содержится ли любая часть указанного прямоугольника в области, представленной текущим объектом, используя указанные графические объекты.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник для проверки |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Контекст графики |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) метод

Определяет, содержится ли любая часть указанного прямоугольника в области, представленной текущим объектом, используя указанные графические объекты.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Прямоугольник для проверки |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Контекст графики |

## Region::IsVisible(float, float) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X проверяемой точки |
| y | **float** | Координата Y проверяемой точки |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const метод

Определяет, содержится ли указанный пункт в области, представленной текущим объектом, используя указанные графические объекты.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X проверяемой точки |
| y | **float** | Координата Y проверяемой точки |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Контекст графики |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Point](../../point/)
* Класс [Region](../)
* Класс [PointF](../../pointf/)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Класс [Graphics](../../graphics/)
* Пространство имен [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)