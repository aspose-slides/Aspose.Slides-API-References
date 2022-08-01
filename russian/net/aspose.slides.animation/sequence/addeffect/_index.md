---
title: AddEffect
second_title: Справочник по API Aspose.Slides для .NET
description: Добавить новый эффект в конец последовательности.
type: docs
weight: 40
url: /ru/net/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Добавить новый эффект в конец последовательности.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | IShape | Объект формы[`IShape`](../../../aspose.slides/ishape) для добавления эффекта |
| effectType | EffectType | Тип эффекта анимации[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Триггерный тип эффекта[`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта[`IEffect`](../../ieffect)

### Смотрите также

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Добавить новый эффект анимации для абзаца в конец последовательности.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | IParagraph | Объект абзаца[`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Тип эффекта анимации[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Триггерный тип эффекта[`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта[`IEffect`](../../ieffect)

### Примеры

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // выделить абзац для добавления эффекта
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // добавить эффект анимации полета к выделенному абзацу
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Смотрите также

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Добавляет новый эффект анимации диаграммы для категории или серии в конец последовательности.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | IChart | Объект диаграммы[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Тип эффекта анимации[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | ИндексInt32 |
| effectType | EffectType | Тип эффекта анимации[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Триггерный тип эффекта[`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта[`IEffect`](../../ieffect)

### Смотрите также

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Добавляет новый эффект анимации диаграммы для элементов категории или серии в конец последовательности.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | IChart | Объект диаграммы[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Тип эффекта анимации[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Индекс серии диаграммInt32 |
| categoriesIndex | Int32 | Индекс категорииInt32 |
| effectType | EffectType | Тип эффекта анимации[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Триггерный тип эффекта[`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта[`IEffect`](../../ieffect)

### Смотрите также

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
