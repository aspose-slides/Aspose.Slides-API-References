---
title: GetTile()
second_title: Aspose.Slides для C++ справка по API
description: Создает изображение плитки для заливки узором с указанными цветами.
type: docs
weight: 53
url: /ru/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) метод

Создаёт изображение плитки для заливки узором с указанными цветами.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Фон [System::Drawing::Color](../../../system.drawing/color/) для узора. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Передний план [System::Drawing::Color](../../../system.drawing/color/) для узора. |

### Возвращаемое значение

Плитка [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) метод

Создаёт изображение плитки для заливки узором.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Значение по умолчанию [System::Drawing::Color](../../../system.drawing/color/) |

### Возвращаемое значение

Плитка [IImage](../../iimage/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [Color](../../../system.drawing/color/)
* Класс [PatternFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)