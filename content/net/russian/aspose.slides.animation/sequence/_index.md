---
title: Последовательность
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет коллекцию последовательностей эффектов.
type: docs
weight: 710
url: /ru/aspose.slides.animation/sequence/
---

## Класс Sequence

Представляет последовательность (коллекцию эффектов).

```csharp
public sealed class Sequence : ISequence
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides.animation/sequence/count) { get; } | Возвращает количество эффектов в последовательности. Свойство только для чтения Int32. |
| [Item](../../aspose.slides.animation/sequence/item) { get; } | Возвращает эффект по указанному индексу. |
| [TriggerShape](../../aspose.slides.animation/sequence/triggershape) { get; set; } | Возвращает или устанавливает целевую фигуру для ИНТЕРАКТИВНОЙ последовательности. Если последовательность не интерактивна, то возвращает null. Читаемое/записываемое [`IShape`](../../aspose.slides/ishape). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_2)(IParagraph, EffectType, EffectSubtype, EffectTriggerType) | Добавляет новый анимационный эффект для абзаца в конец последовательности. |
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_3)(IShape, EffectType, EffectSubtype, EffectTriggerType) | Добавляет новый эффект в конец последовательности. |
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect)(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) | Добавляет новый анимационный эффект для категории или серии к концу последовательности. |
| [AddEffect](../../aspose.slides.animation/sequence/addeffect#addeffect_1)(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) | Добавляет новый анимационный эффект для элементов в категории или серии к концу последовательности. |
| [Clear](../../aspose.slides.animation/sequence/clear)() | Удаляет все эффекты из коллекции. |
| [GetCount](../../aspose.slides.animation/sequence/getcount)(IShape) | Возвращает количество эффектов для указанной фигуры. |
| [GetEffectsByParagraph](../../aspose.slides.animation/sequence/geteffectsbyparagraph)(IParagraph) | Возвращает массив эффектов для указанного абзаца. |
| [GetEffectsByShape](../../aspose.slides.animation/sequence/geteffectsbyshape)(IShape) | Возвращает массив эффектов для указанной фигуры. |
| [GetEnumerator](../../aspose.slides.animation/sequence/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Remove](../../aspose.slides.animation/sequence/remove)(IEffect) | Удаляет указанный эффект из коллекции. |
| [RemoveAt](../../aspose.slides.animation/sequence/removeat)(int) | Удаляет эффект из коллекции. |
| [RemoveByShape](../../aspose.slides.animation/sequence/removebyshape)(IShape) | Удаляет эффект для указанной фигуры. |

### Смотрите также

* интерфейс [ISequence](../isequence)
* пространство имен [Aspose.Slides.Animation](../../aspose.slides.animation)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->