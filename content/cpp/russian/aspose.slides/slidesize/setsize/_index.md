---
title: SetSize()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает размер слайда по типу и масштабирует существующее содержимое.
type: docs
weight: 53
url: /ru/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) метод

Устанавливает размер слайда по типу и масштабирует существующее содержимое.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Предопределённый размер слайда, который следует применить. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Режим масштабирования содержимого, который следует использовать. |
## Замечания

Присваивание любого значения, отличного от [SlideSizeType::Custom](../../slidesizetype/), изменяет [SlideSize::get_Size](../get_size/) в соответствии с выбранным типом, при этом сохраняет [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) метод

Устанавливает размеры слайда явно и масштабирует существующее содержимое.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | **float** | Новая ширина слайда в пунктах. |
| height | **float** | Новая высота слайда в пунктах. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Режим масштабирования содержимого, который следует использовать. |
## Замечания

Это сбрасывает свойство [SlideSize::get_Type](../get_type/) в значение [SlideSizeType::Custom](../../slidesizetype/) и устанавливает [Orientation](../../orientation/). 

## Смотрите также

* Перечисление [SlideSizeType](../../slidesizetype/)
* Перечисление [SlideSizeScaleType](../../slidesizescaletype/)
* Класс [SlideSize](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)