---
title: DrawArc()
second_title: Aspose.Slides для C++ справочник API
description: Рисует указанную дугу, используя заданное перо, на поверхности, представленной текущим объектом.
type: docs
weight: 248
url: /ru/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) метод


Рисует заданную дугу, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании дуги |
| x | **int32_t** | Координата X верхнего левого угла прямоугольника, задающего эллипс |
| y | **int32_t** | Координата Y верхнего левого угла прямоугольника, задающего эллипс |
| width | **int32_t** | Ширина прямоугольника, задающего эллипс |
| height | **int32_t** | Высота прямоугольника, задающего эллипс |
| startAngle | **int32_t** | Угол в градусах, измеряемый по часовой стрелке от оси X до начальной точки дуги |
| sweepAngle | **int32_t** | Угол в градусах, измеряемый по часовой стрелке от **startAngle** до конечной точки дуги |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) метод


Рисует заданную дугу, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании дуги |
| x | **float** | Координата X верхнего левого угла прямоугольника, задающего эллипс |
| y | **float** | Координата Y верхнего левого угла прямоугольника, задающего эллипс |
| width | **float** | Ширина прямоугольника, задающего эллипс |
| height | **float** | Высота прямоугольника, задающего эллипс |
| startAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от оси X до начальной точки дуги |
| sweepAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от **startAngle** до конечной точки дуги |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) метод


Рисует заданную дугу, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании дуги |
| rect | [Rectangle](../../rectangle/) | Прямоугольник, задающий эллипс |
| startAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от оси X до начальной точки дуги |
| sweepAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от **startAngle** до конечной точки дуги |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) метод


Рисует заданную дугу, используя указанный перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании дуги |
| rect | [RectangleF](../../rectanglef/) | Прямоугольник, задающий эллипс |
| startAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от оси X до начальной точки дуги |
| sweepAngle | **float** | Угол в градусах, измеряемый по часовой стрелке от **startAngle** до конечной точки дуги |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Pen](../../pen/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)