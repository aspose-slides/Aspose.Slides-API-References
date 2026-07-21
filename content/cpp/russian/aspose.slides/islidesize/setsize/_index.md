---
title: SetSize()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает размер слайда по типу и масштабирует существующее содержимое. Присваивание любого значения, отличного от SlideSizeType::Custom, изменяет ISlideSize::get_Size в соответствии с выбранным типом, при этом сохраняет ISlideSize::get_Orientation."
type: docs
weight: 53
url: /ru/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) метод

Устанавливает размер слайда по типу и масштабирует существующее содержимое. Присваивание любого значения, отличного от [SlideSizeType::Custom](../../slidesizetype/), изменяет [ISlideSize::get_Size](../get_size/) в соответствии с выбранным типом, при этом сохраняет [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Предопределенный размер слайда, который следует применить. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Режим масштабирования содержимого, который следует использовать. |
## Примечания

Присваивание любого значения, отличного от [SlideSizeType::Custom](../../slidesizetype/), изменяет [System::Drawing::Size](../../../system.drawing/size/) в соответствии с выбранным типом, при этом сохраняет [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) метод

Устанавливает размеры слайда явно и масштабирует существующее содержимое. Это сбрасывает значение [ISlideSize::get_Type](../get_type/) на [SlideSizeType::Custom](../../slidesizetype/) и задает [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | **float** | Новая ширина слайда в пунктах. |
| height | **float** | Новая высота слайда в пунктах. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Режим масштабирования содержимого, который следует использовать. |
## Примечания

Это сбрасывает свойство [ISlideSize::get_Type](../get_type/) до [SlideSizeType::Custom](../../slidesizetype/) и задает [Orientation](../../orientation/). 

## См. также

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)