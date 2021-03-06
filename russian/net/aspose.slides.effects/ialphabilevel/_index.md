---
title: IAlphaBiLevel
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет эффект двухуровневого альфа-канала. Значения альфа-канала непрозрачности меньшие порогового значения изменяются на 0 полностью прозрачные а значения альфа-канала превышающие пороговое значение или равные ему изменяются на 100  полностью непрозрачные.
type: docs
weight: 2840
url: /ru/net/aspose.slides.effects/ialphabilevel/
---
## IAlphaBiLevel interface

Представляет эффект двухуровневого альфа-канала. Значения альфа-канала (непрозрачности), меньшие порогового значения, изменяются на 0 (полностью прозрачные), а значения альфа-канала, превышающие пороговое значение или равные ему, изменяются на 100 % (полностью непрозрачные).

```csharp
public interface IAlphaBiLevel : IAccessiblePVIObject<IAlphaBiLevelEffectiveData>, 
    IImageTransformOperation
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIAccessiblePVIObject](../../aspose.slides.effects/ialphabilevel/asiaccessiblepviobject) { get; } | Позволяет получить базовый интерфейс IAccessiblePVIObject. Только для чтения[`IAccessiblePVIObject`](../../aspose.slides/iaccessiblepviobject-1) . |
| [AsIImageTransformOperation](../../aspose.slides.effects/ialphabilevel/asiimagetransformoperation) { get; } | Позволяет получить базовый интерфейс IImageTransformOperation. Только для чтения[`IImageTransformOperation`](../iimagetransformoperation) . |
| [Threshold](../../aspose.slides.effects/ialphabilevel/threshold) { get; set; } | Возвращает порог эффекта. Чтение/записьSingle . |

### Примечания

Используйте ImageTransformOperationFactory для создания экземпляров в COM.

### Смотрите также

* interface [IAccessiblePVIObject&lt;T&gt;](../../aspose.slides/iaccessiblepviobject-1)
* interface [IAlphaBiLevelEffectiveData](../ialphabileveleffectivedata)
* interface [IImageTransformOperation](../iimagetransformoperation)
* пространство имен [Aspose.Slides.Effects](../../aspose.slides.effects)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
