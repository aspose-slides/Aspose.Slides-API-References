---
title: AddArc()
second_title: Aspose.Slides для C++ справка API
description: Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом.
type: docs
weight: 183
url: /ru/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) метод

Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X верхнего левого угла прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| y | **float** | Координата Y верхнего левого угла прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| width | **float** | Ширина прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| height | **float** | Высота прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| startAngle | **float** | Указывает начальный угол дуги в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом дуги |

## GraphicsPath::AddArc(int, int, int, int, float, float) метод

Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата X верхнего левого угла прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| y | int | Координата Y верхнего левого угла прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| width | int | Ширина прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| height | int | Высота прямоугольника, ограничивающего эллипс, из которого чертится дуга |
| startAngle | **float** | Указывает начальный угол дуги в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом дуги |

## GraphicsPath::AddArc(const RectangleF\&, float, float) метод

Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | Прямоугольник, ограничивающий эллипс, из которого чертится дуга |
| startAngle | **float** | Указывает начальный угол дуги в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом дуги |

## GraphicsPath::AddArc(const Rectangle\&, float, float) метод

Добавляет указанную эллиптическую дугу к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Прямоугольник, ограничивающий эллипс, из которого чертится дуга |
| startAngle | **float** | Указывает начальный угол дуги в градусах, измеряемый по часовой стрелке от оси X |
| sweepAngle | **float** | Указывает угол между начальным углом и концом дуги |

## См. также

* Класс [GraphicsPath](../)
* Класс [RectangleF](../../../system.drawing/rectanglef/)
* Класс [Rectangle](../../../system.drawing/rectangle/)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)