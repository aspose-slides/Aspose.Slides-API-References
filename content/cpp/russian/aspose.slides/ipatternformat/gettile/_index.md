---
title: GetTile()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт изображение тайла для заливки узором с указанными цветами.
type: docs
weight: 53
url: /ru/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) метод

Создает изображение тайла для заливки узора с указанными цветами.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Фоновый [System::Drawing::Color](../../../system.drawing/color/) для узора. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Передний [System::Drawing::Color](../../../system.drawing/color/) для узора. |

### Возвращаемое значение

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) метод

Создает изображение тайла для заливки узора.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Типовой [System::Drawing::Color](../../../system.drawing/color/), определенный в объекте StyleEx класса ShapeEx. Цвета заливки могут зависеть от него. |

### Возвращаемое значение

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)