---
title: LayoutSlideCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет базовый класс для коллекции слайдов макета.
type: docs
weight: 6950
url: /ru/net/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection class

Представляет базовый класс для коллекции слайдов макета.

```csharp
public class LayoutSlideCollection : ILayoutSlideCollection
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/layoutslidecollection/count) { get; } | Возвращает количество слайдов макета в коллекции. Только для чтенияInt32. |
| [IsSynchronized](../../aspose.slides/layoutslidecollection/issynchronized) { get; } | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только чтениеBoolean. |
| [Item](../../aspose.slides/layoutslidecollection/item) { get; } | Возвращает макет слайда по индексу. Только для чтения[`LayoutSlide`](../layoutslide). |
| [SyncRoot](../../aspose.slides/layoutslidecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтенияObject. |

## Методы

| Имя | Описание |
| --- | --- |
| [CopyTo](../../aspose.slides/layoutslidecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetByType](../../aspose.slides/layoutslidecollection/getbytype)(SlideLayoutType) | Возвращает первый макет слайда указанного типа.  Тип макета слайда для поиска.[`LayoutSlide`](../layoutslide)с указанным типом или null, если макеты не найдены. |
| [GetEnumerator](../../aspose.slides/layoutslidecollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Remove](../../aspose.slides/layoutslidecollection/remove)(ILayoutSlide) | Удаляет макет из коллекции. |
| [RemoveUnused](../../aspose.slides/layoutslidecollection/removeunused)() | Удаляет неиспользуемые слайды макета (слайды макета, HasDependingSlides которых имеет значение false). |

### Смотрите также

* interface [ILayoutSlideCollection](../ilayoutslidecollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->