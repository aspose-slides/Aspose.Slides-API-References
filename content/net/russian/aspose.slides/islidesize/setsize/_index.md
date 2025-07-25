---
title: SetSize
second_title: Aspose.Sildes для .NET API Reference
description: Устанавливает тип размера слайда и масштабирует контент с использованием типа масштабирования. Присвоение любого значения, кроме Custom, изменит Sizeaspose.slides/islidesize/size соответствующим образом, но сохранит Orientationaspose.slides/islidesize/orientation нетронутым.
type: docs
weight: 40
url: /ru/aspose.slides/islidesize/setsize/
---

## SetSize(SlideSizeType, SlideSizeScaleType) {#setsize}

Устанавливает тип размера слайда и масштабирует контент с использованием типа масштабирования. Присвоение любого значения, кроме Custom, изменит [`Size`](../size) соответствующим образом, но сохранит [`Orientation`](../orientation) нетронутым.

```csharp
public void SetSize(SlideSizeType type, SlideSizeScaleType scaleType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | SlideSizeType | Тип размера слайда. |
| scaleType | SlideSizeScaleType | Тип масштабирования контента слайда. |

### Смотрите также

* enum [SlideSizeType](../../slidesizetype)
* enum [SlideSizeScaleType](../../slidesizescaletype)
* interface [ISlideSize](../../islidesize)
* namespace [Aspose.Slides](../../islidesize)
* assembly [Aspose.Slides](../../../)

---

## SetSize(float, float, SlideSizeScaleType) {#setsize_1}

Устанавливает размер в пунктах и масштабирует контент с использованием типа масштабирования. Присвоение любого значения сбросит [`Type`](../type) свойство на Custom и установит [`Orientation`](../orientation).

```csharp
public void SetSize(float width, float height, SlideSizeScaleType scaleType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Single | Ширина. |
| height | Single | Высота. |
| scaleType | SlideSizeScaleType | Тип масштабирования контента слайда. |

### Смотрите также

* enum [SlideSizeScaleType](../../slidesizescaletype)
* interface [ISlideSize](../../islidesize)
* namespace [Aspose.Slides](../../islidesize)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->