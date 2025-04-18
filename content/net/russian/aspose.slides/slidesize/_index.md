---
title: SlideSize
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет размер слайда.
type: docs
weight: 9700
url: /ru/aspose.slides/slidesize/
---
## SlideSize class

Представляет размер слайда.

```csharp
public class SlideSize : DomObject<Presentation>, ISlideSize
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Orientation](../../aspose.slides/slidesize/orientation) { get; set; } | Возвращает или задает ориентацию слайда.  Изменение этого значения поменяет местами размеры слайда. Чтение/запись[`SlideOrientation`](../slideorientation). |
| [Size](../../aspose.slides/slidesize/size) { get; } | Возвращает или задает размер в пунктах.  Присвоение любого значения приведет к сбросу[`Type`](./type) свойствоCustomи установите[`Orientation`](./orientation) . Чтение/записьSizeF. |
| [Type](../../aspose.slides/slidesize/type) { get; } | Возвращает или задает тип размера слайда.  Присвоение любого значения, кромеCustomизменится[`Size`](./size) соответственно, но сохранит[`Orientation`](./orientation) нетронутыми. Чтение/запись[`SlideSizeType`](../slidesizetype). |

## Методы

| Имя | Описание |
| --- | --- |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize)(SlideSizeType, SlideSizeScaleType) | Устанавливает тип размера слайда и масштабирует содержимое, используя тип масштаба.  Присвоение любого значения, кромеCustomизменится[`Size`](./size) соответственно, но сохранит[`Orientation`](./orientation) нетронутыми. |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize_1)(float, float, SlideSizeScaleType) | Устанавливает размер в пунктах и масштабирует содержимое, используя тип масштаба.  Присвоение любого значения приведет к сбросу[`Type`](./type) свойствоCustomи установите[`Orientation`](./orientation) . |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideSize](../islidesize)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
