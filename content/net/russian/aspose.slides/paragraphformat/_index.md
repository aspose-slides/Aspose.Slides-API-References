---
title: ParagraphFormat
second_title: Aspose.Sildes для .NET API Справочник
description: Этот класс содержит свойства форматирования абзацев. В отличие от IParagraphFormatEffectiveData, все свойства этого класса могут быть записаны.
type: docs
weight: 9040
url: /ru/aspose.slides/paragraphformat/
---

## Класс ParagraphFormat

Этот класс содержит свойства форматирования абзацев. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса могут быть записаны.

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
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Возвращает или устанавливает выравнивание текста в абзаце без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Возвращает или устанавливает размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли разрыв строки для восточноазиатских языков в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Возвращает или устанавливает выравнивание шрифта в абзаце без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Возвращает или устанавливает отступ первой строки / висячий отступ абзаца без наследования. Висячий отступ может быть определен с отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Определяет, используется ли разрыв строки для латинских языков в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Возвращает или устанавливает левый отступ в абзаце без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Возвращает или устанавливает правый отступ в абзаце без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Возвращает или устанавливает количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение указывает размер пробела в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Возвращает или устанавливает количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение указывает размер пробела в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Возвращает или устанавливает количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное - размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### Примечания

Этот класс используется для возврата и манипуляции свойствами форматирования абзацев, определенными для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие "неопределенно".

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, вам необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* интерфейс [IParagraphFormat](../iparagraphformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->