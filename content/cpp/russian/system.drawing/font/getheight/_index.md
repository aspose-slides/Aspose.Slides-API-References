---
title: GetHeight()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает межстрочный интервал шрифта, представленного текущим объектом, в текущих единицах измерения заданного объекта Graphics.
type: docs
weight: 14
url: /ru/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) метод


Returns the line spacing of the font represented by the current object, in the current unit of a specified [Graphics](../../graphics/) object.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Объект [Graphics](../../graphics/), определяющий единицы измерения |

## Font::GetHeight(float) метод


Returns the height of the font represented by the current object when drawn to a display device with the specified vertical resolution.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi | **float** | Вертикальное разрешение дисплейного устройства |

### Возвращаемое значение

Высота шрифта в пикселях

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Graphics](../../graphics/)
* Класс [Font](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)