---
title: IParagraphFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Этот класс содержит свойства форматирования абзаца. В отличие отIParagraphFormatEffectiveData./iparagraphformateffectivedataвсе свойства этого класса доступны для записи.
type: docs
weight: 6030
url: /ru/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Этот класс содержит свойства форматирования абзаца. В отличие от[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)все свойства этого класса доступны для записи.

```csharp
public interface IParagraphFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Возвращает или задает выравнивание текста в абзаце без наследования. Чтение/запись[`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Возвращает маркированный формат абзаца. Только для чтения[`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Возвращает формат части абзаца по умолчанию. Наследование не применяется. Только для чтения[`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Возвращает или устанавливает размер табуляции по умолчанию без наследования. Чтение/записьSingle. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Возвращает или задает глубину абзаца. Значение 0 означает неопределенное значение. Чтение/записьInt16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли восточноазиатский разрыв строки в абзаце. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Возвращает или задает выравнивание шрифта в абзаце без наследования. Чтение/запись[`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Определяет, используются ли в абзаце висячие знаки препинания. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Возвращает или задает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть определен отрицательными значениями. Чтение/записьSingle. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Определяет, используется ли в абзаце разрыв строки на латинице. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Возвращает или устанавливает левое поле в абзаце без наследования. Чтение/записьSingle. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Возвращает или устанавливает правое поле в абзаце без наследования. Чтение/записьSingle. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Определяет, используется ли в абзаце написание справа налево. Наследование не применяется. Чтение/запись[`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Возвращает или задает количество места после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение определяет размер пробела в пунктах. Чтение/записьSingle. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Возвращает или задает количество места перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять пробел. Отрицательное значение определяет размер пробела в пунктах. Чтение/записьSingle. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Возвращает или задает расстояние между базовыми строками в абзаце. Положительное значение означает процент, отрицательное - размер в пунктах. Наследование не применяется. Чтение/записьSingle. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Возвращает таблицы абзаца. Наследование не применяется. Только для чтения[`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применением наследования. |

### Примечания

Этот класс используется для возврата и управления свойствами форматирования абзаца, определенными для конкретного абзаца. Это означает, что при получении значений не применяется наследование, поэтому в большинстве случаев вы получите значения, означающие «неопределенные».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, вам необходимо использовать метод[`GetEffective`](./geteffective) который возвращает экземпляр[`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
