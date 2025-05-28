---
title: IChartTextBlockFormat
second_title: Aspose.Sildes для .NET API Reference
description: Представляет свойства форматирования для текстовых элементов графиков.
type: docs
weight: 1900
url: /ru/aspose.slides.charts/icharttextblockformat/
---

## Интерфейс IChartTextBlockFormat

Представляет свойства форматирования для текстовых элементов графиков.

```csharp
public interface IChartTextBlockFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AnchoringType](../../aspose.slides.charts/icharttextblockformat/anchoringtype) { get; set; } | Возвращает или устанавливает вертикальную привязку текста в TextFrame. Чтение/запись [`TextAnchorType`](../../aspose.slides/textanchortype). |
| [AutofitType](../../aspose.slides.charts/icharttextblockformat/autofittype) { get; set; } | Возвращает или устанавливает режим автоматической подгонки текста. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта для рендеринга). Чтение/запись [`TextAutofitType`](../../aspose.slides/textautofittype). |
| [CenterText](../../aspose.slides.charts/icharttextblockformat/centertext) { get; set; } | Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке. Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |
| [MarginBottom](../../aspose.slides.charts/icharttextblockformat/marginbottom) { get; set; } | Возвращает или устанавливает нижний отступ (пункты) в TextFrame. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта для рендеринга). Чтение/запись Double. |
| [MarginLeft](../../aspose.slides.charts/icharttextblockformat/marginleft) { get; set; } | Возвращает или устанавливает левый отступ (пункты) в TextFrame. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта для рендеринга). Чтение/запись Double. |
| [MarginRight](../../aspose.slides.charts/icharttextblockformat/marginright) { get; set; } | Возвращает или устанавливает правый отступ (пункты) в TextFrame. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта для рендеринга). Чтение/запись Double. |
| [MarginTop](../../aspose.slides.charts/icharttextblockformat/margintop) { get; set; } | Возвращает или устанавливает верхний отступ (пункты) в TextFrame. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта для рендеринга). Чтение/запись Double. |
| [RotationAngle](../../aspose.slides.charts/icharttextblockformat/rotationangle) { get; set; } | Указывает пользовательское вращение, которое применяется к тексту внутри ограничивающего прямоугольника. Если оно не указано, используется вращение сопутствующей формы. Если оно указано, то применяется независимо от формы. То есть, форма может иметь применённое вращение, в дополнение к тому, что текст сам по себе имеет применённое вращение. Результирующее значение визуального вращения текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись Single. |
| [TextVerticalType](../../aspose.slides.charts/icharttextblockformat/textverticaltype) { get; set; } | Определяет ориентацию текста. Результирующее значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [`TextVerticalType`](../../aspose.slides/textverticaltype). |
| [WrapText](../../aspose.slides.charts/icharttextblockformat/wraptext) { get; set; } | **True**, если текст оборачивается по краям TextFrame. Изменение этого свойства может оказать влияние только на эти части графиков: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2007/2013). Чтение/запись [`NullableBool`](../../aspose.slides/nullablebool). |

### См. также

* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->