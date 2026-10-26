---
title: DrawPie()
second_title: Справочник API Aspose.Slides для C++
description: Рисует указанный сектор, используя указанное перо, на поверхности, представленной текущим объектом.
type: docs
weight: 261
url: /ru/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) метод

Рисует указанный сектор, используя указанное перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сектора |
| x | **int32_t** | Координата X верхнего левого угла прямоугольника, определяющего эллипс |
| y | **int32_t** | Координата Y верхнего левого угла прямоугольника, определяющего эллипс |
| width | **int32_t** | Ширина прямоугольника, определяющего эллипс |
| height | **int32_t** | Высота прямоугольника, определяющего эллипс |
| startAngle | **int32_t** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **int32_t** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) метод

Рисует указанный сектор, используя указанное перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сектора |
| x | **float** | Координата X верхнего левого угла прямоугольника, определяющего эллипс |
| y | **float** | Координата Y верхнего левого угла прямоугольника, определяющего эллипс |
| width | **float** | Ширина прямоугольника, определяющего эллипс |
| height | **float** | Высота прямоугольника, определяющего эллипс |
| startAngle | **float** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **float** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) метод

Рисует указанный сектор, используя указанное перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сектора |
| rect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий эллипс |
| startAngle | **float** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **float** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) метод

Рисует указанный сектор, используя указанное перо, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сектора |
| rect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий эллипс |
| startAngle | **float** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **float** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Pen](../../pen/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)