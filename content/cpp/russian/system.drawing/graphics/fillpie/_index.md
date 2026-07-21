---
title: FillPie()
second_title: Справочник API Aspose.Slides для C++
description: Заполняет указанный сектор, используя указанную кисть, на поверхности, представленной текущим объектом.
type: docs
weight: 274
url: /ru/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) method

Заполняет указанный сектор, используя указанную кисть, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Кисть, используемая при заполнении сектора |
| x | int | Координата X верхнего левого угла прямоугольника, определяющего эллипс |
| y | int | Координата Y верхнего левого угла прямоугольника, определяющего эллипс |
| width | int | Ширина прямоугольника, определяющего эллипс |
| height | int | Высота прямоугольника, определяющего эллипс |
| startAngle | int | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | int | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) method

Заполняет указанный сектор, используя указанную кисть, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Кисть, используемая при заполнении сектора |
| x | **float** | Координата X верхнего левого угла прямоугольника, определяющего эллипс |
| y | **float** | Координата Y верхнего левого угла прямоугольника, определяющего эллипс |
| width | **float** | Ширина прямоугольника, определяющего эллипс |
| height | **float** | Высота прямоугольника, определяющего эллипс |
| startAngle | **float** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **float** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) method

Заполняет указанный сектор, используя указанную кисть, на поверхности, представленной текущим объектом.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Кисть, используемая при заполнении сектора |
| rect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий эллипс |
| startAngle | **float** | Угол в градусах, измеренный по часовой стрелке от оси X до начальной точки сектора |
| sweepAngle | **float** | Угол в градусах, измеренный по часовой стрелке от **startAngle** до конечной точки сектора |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Brush](../../brush/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)