---
title: ILayoutSlide
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет слайд-макет.
type: docs
weight: 6020
url: /ru/aspose.slides/ilayoutslide/
---

## Интерфейс ILayoutSlide

Представляет слайд-макет.

```csharp
public interface ILayoutSlide : IBaseSlide, IOverrideThemeable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/ilayoutslide/asibaseslide) { get; } | Позволяет получить базовый интерфейс IBaseSlide. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [AsIOverrideThemeable](../../aspose.slides/ilayoutslide/asioverridethemeable) { get; } | Возвращает интерфейс IOverrideThemeable. Только для чтения [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [HasDependingSlides](../../aspose.slides/ilayoutslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, который зависит от этого слайда-макета. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/ilayoutslide/headerfootermanager) { get; } | Возвращает менеджер заголовков и подвалов слайда-макета. Только для чтения [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [LayoutType](../../aspose.slides/ilayoutslide/layouttype) { get; } | Возвращает тип макета этого слайда-макета. Только для чтения [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/ilayoutslide/masterslide) { get; set; } | Возвращает или задает мастер-слайд для макета. Чтение/запись [`IMasterSlide`](../imasterslide). |
| [PlaceholderManager](../../aspose.slides/ilayoutslide/placeholdermanager) { get; } | Возвращает менеджер заполнителей слайда-макета. Только для чтения [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetDependingSlides](../../aspose.slides/ilayoutslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого слайда-макета. |
| [Remove](../../aspose.slides/ilayoutslide/remove)() | Удаляет макет из презентации. |

### Смотрите также

* интерфейс [IBaseSlide](../ibaseslide)
* интерфейс [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->