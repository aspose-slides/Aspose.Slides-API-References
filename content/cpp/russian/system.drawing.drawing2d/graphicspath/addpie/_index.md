---
title: AddPie()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанный контур формы пирога к пути, представляемому текущим объектом.
type: docs
weight: 209
url: /ru/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) метод

Добавляет указанный контур формы пирога к пути, представляемому текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| y | **float** | Координата Y верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| width | **float** | Ширина верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| height | **float** | Высота верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| startAngle | **float** | Указывает начальный угол пирога в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом пирога |

## GraphicsPath::AddPie(int, int, int, int, float, float) метод

Добавляет указанный контур формы пирога к пути, представляемому текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата X верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| y | int | Координата Y верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| width | int | Ширина верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| height | int | Высота верхнего левого угла прямоугольника, ограничивающего эллипс, из которого рисуется пирог |
| startAngle | **float** | Указывает начальный угол пирога в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом пирога |

## GraphicsPath::AddPie(const Rectangle\&, float, float) метод

Добавляет указанный контур формы пирога к пути, представляемому текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Прямоугольник, ограничивающий эллипс, из которого рисуется пирог |
| startAngle | **float** | Указывает начальный угол пирога в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом пирога |

## См. также

* Класс [GraphicsPath](../)
* Класс [Rectangle](../../../system.drawing/rectangle/)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)