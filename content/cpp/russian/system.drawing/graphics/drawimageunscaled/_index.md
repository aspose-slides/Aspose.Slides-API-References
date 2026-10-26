---
title: DrawImageUnscaled()
second_title: Справочник API Aspose.Slides для C++
description: Отрисовывает указанное изображение в его оригинальном физическом размере в указанном месте.
type: docs
weight: 443
url: /ru/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) метод

Отрисовывает указанное изображение в его исходном физическом размере в заданном месте.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | int | Координата X верхнего левого угла отрисованного изображения |
| y | int | Координата Y верхнего левого угла отрисованного изображения |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) метод

Отрисовывает указанное изображение в его исходном физическом размере в заданном месте.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| x | int | Координата X верхнего левого угла отрисованного изображения |
| y | int | Координата Y верхнего левого угла отрисованного изображения |
| width | int | Не используется |
| height | int | Не используется |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) метод

Отрисовывает указанное изображение в его исходном физическом размере в заданном месте.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий верхний левый угол отрисованного изображения. Свойства X и Y прямоугольника задают верхний левый угол. Значения ширины и высоты игнорируются. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) метод

Отрисовывает указанное изображение в его исходном физическом размере в заданном месте.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Изображение для отрисовки |
| point | const [Point](../../point/)\& | Структура [Point](../../point/), определяющая верхний левый угол отрисованного изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Image](../../image/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Класс [Point](../../point/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)