---
title: ParagraphFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Этот класс содержит свойства форматирования абзаца. В отличие отIParagraphFormatEffectiveData./iparagraphformateffectivedataвсе свойства этого класса доступны для записи.
type: docs
weight: 8580
url: /ru/aspose.slides/paragraphformat/
---
## ParagraphFormat class

Этот класс содержит свойства форматирования абзаца. В отличие от[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)все свойства этого класса доступны для записи.

```csharp
public class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Инициализирует новый экземпляр класса[`ParagraphFormat`](../paragraphformat). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Возвращает или задает выравнивание текста в абзаце без наследования. Чтение/запись[`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Возвращает или устанавливает размер табуляции по умолчанию без наследования. Чтение/записьSingle. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли восточноазиатский разрыв строки в абзаце. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Возвращает или задает выравнивание шрифта в абзаце без наследования. Чтение/запись[`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Определяет, используются ли в абзаце висячие знаки препинания. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Возвращает или задает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть определен отрицательными значениями. Чтение/записьSingle. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Определяет, используется ли в абзаце разрыв строки на латинице. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Возвращает или устанавливает левое поле в абзаце без наследования. Чтение/записьSingle. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Возвращает или устанавливает правое поле в абзаце без наследования. Чтение/записьSingle. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Определяет, используется ли в абзаце написание справа налево. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Возвращает или задает количество места после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение определяет размер пробела в пунктах. Чтение/записьSingle. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Возвращает или задает количество места перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение определяет размер пробела в пунктах. Чтение/записьSingle. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Возвращает или задает расстояние между базовыми строками в абзаце. Положительное значение означает процент, отрицательное - размер в пунктах. Наследование не применяется. Чтение/записьSingle. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Возвращает таблицы абзаца. Наследование не применяется. Только для чтения[`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Примечания

Этот класс используется для возврата и управления свойствами форматирования абзаца, определенными для конкретного абзаца. Это означает, что при получении значений не применяется наследование, поэтому в большинстве случаев вы получите значения, означающие «неопределенные».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, вам необходимо использовать метод[`GetEffective`](./geteffective) который возвращает экземпляр[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Смотрите также

* class [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
