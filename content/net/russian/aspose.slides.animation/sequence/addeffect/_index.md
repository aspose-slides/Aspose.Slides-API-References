---
title: AddEffect
second_title: Aspose.Sildes для .NET API Reference
description: Добавить новый эффект в конце последовательности.
type: docs
weight: 40
url: /ru/aspose.slides.animation/sequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Добавить новый эффект в конце последовательности.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | IShape | Объект формы [`IShape`](../../../aspose.slides/ishape) для добавления эффекта |
| effectType | EffectType | Тип анимационного эффекта [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Тип триггера эффекта [`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта [`IEffect`](../../ieffect)

### См. также

* интерфейс [IEffect](../../ieffect)
* интерфейс [IShape](../../../aspose.slides/ishape)
* перечисление [EffectType](../../effecttype)
* перечисление [EffectSubtype](../../effectsubtype)
* перечисление [EffectTriggerType](../../effecttriggertype)
* класс [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Добавить новый анимационный эффект для абзаца в конце последовательности.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | IParagraph | Объект абзаца [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Тип анимационного эффекта [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Тип триггера эффекта [`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта [`IEffect`](../../ieffect)

### Примеры

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // выбрать абзац для добавления эффекта
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // добавить эффект анимации полета к выбранному абзацу
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### См. также

* интерфейс [IEffect](../../ieffect)
* интерфейс [IParagraph](../../../aspose.slides/iparagraph)
* перечисление [EffectType](../../effecttype)
* перечисление [EffectSubtype](../../effectsubtype)
* перечисление [EffectTriggerType](../../effecttriggertype)
* класс [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Добавляет новый анимационный эффект для категории или серии в конце последовательности.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | IChart | Объект диаграммы [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Тип анимационного эффекта [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Индекс Int32 |
| effectType | EffectType | Тип анимационного эффекта [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Тип триггера эффекта [`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта [`IEffect`](../../ieffect)

### См. также

* интерфейс [IEffect](../../ieffect)
* интерфейс [IChart](../../../aspose.slides.charts/ichart)
* перечисление [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* перечисление [EffectType](../../effecttype)
* перечисление [EffectSubtype](../../effectsubtype)
* перечисление [EffectTriggerType](../../effecttriggertype)
* класс [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Добавляет новый анимационный эффект для элементов в категории или серии в конце последовательности.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| chart | IChart | Объект диаграммы [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Тип анимационного эффекта [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Индекс серии диаграммы Int32 |
| categoriesIndex | Int32 | Индекс категории Int32 |
| effectType | EffectType | Тип анимационного эффекта [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Подтипы анимационного эффекта [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Тип триггера эффекта [`EffectTriggerType`](../../effecttriggertype) |

### Возвращаемое значение

Новый объект эффекта [`IEffect`](../../ieffect)

### См. также

* интерфейс [IEffect](../../ieffect)
* интерфейс [IChart](../../../aspose.slides.charts/ichart)
* перечисление [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* перечисление [EffectType](../../effecttype)
* перечисление [EffectSubtype](../../effectsubtype)
* перечисление [EffectTriggerType](../../effecttriggertype)
* класс [Sequence](../../sequence)
* пространство имен [Aspose.Slides.Animation](../../sequence)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->