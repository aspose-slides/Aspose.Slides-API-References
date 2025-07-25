---
title: Background
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет фон слайда.
type: docs
weight: 850
url: /ru/aspose.slides/background/
---

## Класс Background

Представляет фон слайда.

```csharp
public sealed class Background : PVIObject, IBackground
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [EffectFormat](../../aspose.slides/background/effectformat) { get; } | Возвращает EffectFormat для заливки BackgroundType.OwnBackground. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/background/fillformat) { get; } | Возвращает FillFormat для заливки BackgroundType.OwnBackground. Только для чтения [`IFillFormat`](../ifillformat). |
| [Presentation](../../aspose.slides/background/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [Slide](../../aspose.slides/background/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [StyleColor](../../aspose.slides/background/stylecolor) { get; } | Возвращает ColorFormat для заливки BackgroundType.Themed. Только для чтения [`IColorFormat`](../icolorformat). |
| [StyleIndex](../../aspose.slides/background/styleindex) { get; set; } | Возвращает индекс заливки BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заливки. 1..999 - индекс. Чтение/запись UInt16. |
| [Type](../../aspose.slides/background/type) { get; set; } | Возвращает тип заливки фона. Чтение/запись [`BackgroundType`](../backgroundtype). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/background/geteffective)() | Получает эффективные данные фона с применённым наследованием. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хэш значения. |

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IBackground](../ibackground)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->