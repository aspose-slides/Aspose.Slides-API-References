---
title: ParagraphFormat
second_title: Aspose.Sildes для .NET справочник API
description: Этот класс содержит свойства форматирования абзаца. В отличие от IParagraphFormatEffectiveData./iparagraphformateffectivedata все свойства этого класса доступны для записи.
type: docs
weight: 9330
url: /ru/aspose.slides/paragraphformat/
---
## ParagraphFormat класс

Этот класс содержит свойства форматирования абзаца. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Инициализирует новый экземпляр класса [`ParagraphFormat`](../paragraphformat). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Возвращает или задаёт выравнивание текста в абзаце без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только чтение [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Возвращает или задаёт размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли разрыв строки восточно-азиатского типа в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Возвращает или задаёт выравнивание шрифта в абзаце без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть задан отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Определяет, используется ли латинский разрыв строки в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Возвращает или задаёт левый отступ в абзаце без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Возвращает или задаёт правый отступ в абзаце без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Возвращает или задаёт количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должно занимать пустое пространство. Отрицательное значение указывает размер пустого пространства в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Возвращает или задаёт количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должно занимать пустое пространство. Отрицательное значение указывает размер пустого пространства в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Возвращает или задаёт количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Возвращает табуляцию абзаца. Наследование не применяется. Только чтение [`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применённым наследованием. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хэша. |

### Замечания

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы будете получать значения, означающие «не определено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* интерфейс [IParagraphFormat](../iparagraphformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->