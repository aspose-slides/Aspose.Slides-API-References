---
title: IColorFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет цвет используемый в презентации.
type: docs
weight: 4990
url: /ru/net/aspose.slides/icolorformat/
---
## IColorFormat interface

Представляет цвет, используемый в презентации.

```csharp
public interface IColorFormat : IFillParamSource
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/icolorformat/asifillparamsource) { get; } | Возвращает интерфейс IFillParamSource. Только для чтения[`IFillParamSource`](../ifillparamsource). |
| [B](../../aspose.slides/icolorformat/b) { get; set; } | Возвращает или задает синюю составляющую цвета. Все преобразования цвета игнорируются. Чтение/записьByte. |
| [Color](../../aspose.slides/icolorformat/color) { get; set; } | Возвращает результирующий цвет (со всеми примененными преобразованиями цвета). Устанавливает цвета RGB и очищает все преобразования цветов. Чтение/записьColor. |
| [ColorTransform](../../aspose.slides/icolorformat/colortransform) { get; } | Возвращает набор цветовых преобразований, примененных к цвету. Только для чтения[`IColorOperationCollection`](../icoloroperationcollection). |
| [ColorType](../../aspose.slides/icolorformat/colortype) { get; set; } | Возвращает или устанавливает метод определения цвета. Чтение/запись[`ColorType`](../colortype). |
| [FloatB](../../aspose.slides/icolorformat/floatb) { get; set; } | Возвращает или задает синюю составляющую цвета. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [FloatG](../../aspose.slides/icolorformat/floatg) { get; set; } | Возвращает или устанавливает зеленый компонент цвета. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [FloatR](../../aspose.slides/icolorformat/floatr) { get; set; } | Возвращает или устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [G](../../aspose.slides/icolorformat/g) { get; set; } | Возвращает или устанавливает зеленый компонент цвета. Все преобразования цвета игнорируются. Чтение/записьByte. |
| [Hue](../../aspose.slides/icolorformat/hue) { get; set; } | Возвращает или задает компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [Luminance](../../aspose.slides/icolorformat/luminance) { get; set; } | Возвращает или задает компонент яркости цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [PresetColor](../../aspose.slides/icolorformat/presetcolor) { get; set; } | Возвращает или устанавливает предустановку цвета. Чтение/запись[`PresetColor`](../presetcolor). |
| [R](../../aspose.slides/icolorformat/r) { get; set; } | Возвращает или устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/записьByte. |
| [Saturation](../../aspose.slides/icolorformat/saturation) { get; set; } | Возвращает или устанавливает компонент насыщенности цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/записьSingle. |
| [SchemeColor](../../aspose.slides/icolorformat/schemecolor) { get; set; } | Возвращает или задает цвет, определенный цветовой схемой. Чтение/запись[`SchemeColor`](../schemecolor). |
| [SystemColor](../../aspose.slides/icolorformat/systemcolor) { get; set; } | Возвращает или задает цвет, указанный в системной таблице цветов. Чтение/запись[`SystemColor`](../systemcolor). |

## Методы

| Имя | Описание |
| --- | --- |
| [CopyFrom](../../aspose.slides/icolorformat/copyfrom)(IColorFormat) | Скопировать цветовой формат из "color". |
| [ToString](../../aspose.slides/icolorformat/tostring)(ColorStringFormat) | ВозвращаетString, представляющий текущий цветовой формат. |

### Смотрите также

* interface [IFillParamSource](../ifillparamsource)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->