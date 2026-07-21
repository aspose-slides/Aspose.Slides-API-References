---
title: BeginContainer()
second_title: Справочник API Aspose.Slides для C++
description: Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.
type: docs
weight: 976
url: /ru/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() метод

Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) метод

Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий масштабное преобразование нового контейнера. Используется вместе с **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий масштабное преобразование нового контейнера. Используется вместе с **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Значение, определяющее единицу измерения нового контейнера |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) метод

Сохраняет контейнер с текущим состоянием этого объекта, открывает и использует новый контейнер и возвращает сохранённый контейнер.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий масштабное преобразование нового контейнера. Используется вместе с **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий масштабное преобразование нового контейнера. Используется вместе с **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Значение, определяющее единицу измерения нового контейнера |

## См. также

* Перечисление [GraphicsUnit](../../graphicsunit/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)