---
title: ParagraphFormat
second_title: Aspose.Sildes для .NET справочник API
description: Этот класс содержит свойства форматирования абзаца. В отличие от IParagraphFormatEffectiveData./iparagraphformateffectivedata все свойства этого класса доступны для записи.
type: docs
weight: 9310
url: /ru/aspose.slides/paragraphformat/
---
## ParagraphFormat класс

Этот класс содержит свойства форматирования абзаца. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Конструкторы

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Инициализирует новый экземпляр класса [`ParagraphFormat`](../paragraphformat). |

## Свойства

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Возвращает или задает выравнивание текста в абзаце без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Возвращает или задает размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Возвращает или задает выравнивание шрифта в абзаце без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Возвращает или задает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ можно задать отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Возвращает или задает левый отступ в абзаце без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Возвращает или задает правый отступ в абзаце без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Определяет, используется ли запись справа налево в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Возвращает или задает количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должно составлять пустое пространство. Отрицательное значение указывает размер пустого пространства в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Возвращает или задает количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должно составлять пустое пространство. Отрицательное значение указывает размер пустого пространства в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Возвращает или задает количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Возвращает табуляцию абзаца. Наследование не применяется. Только для чтения [`ITabCollection`](../itabcollection). |

## Методы

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применённым наследованием. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено». Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* интерфейс [IParagraphFormat](../iparagraphformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->