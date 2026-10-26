---
title: GetTile()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт изображение плитки для заливки узором с указанными цветами.
type: docs
weight: 53
url: /ru/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) метод

Создаёт изображение плитки для заливки узором с указанными цветами.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Фоновый [System::Drawing::Color](../../../system.drawing/color/) для узора. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Передний план [System::Drawing::Color](../../../system.drawing/color/) для узора. |

### Возвращаемое значение

Плитка [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) метод

Создаёт изображение плитки для заливки узором.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Значение по умолчанию [System::Drawing::Color](../../../system.drawing/color/), определённое в объекте StyleEx класса ShapeEx. Цвета заполнения могут зависеть от него. |

### Возвращаемое значение

Плитка [IImage](../../iimage/).

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [Color](../../../system.drawing/color/)
* Класс [IPatternFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)