---
title: IParagraphFormat
second_title: Aspose.Sildes для .NET справочник API
description: Этот класс содержит свойства форматирования абзаца. В отличие от IParagraphFormatEffectiveData./iparagraphformateffectivedata все свойства этого класса доступны для записи.
type: docs
weight: 6590
url: /ru/aspose.slides/iparagraphformat/
---
## IParagraphFormat интерфейс

Этот класс содержит свойства форматирования абзаца. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public interface IParagraphFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Возвращает или задаёт выравнивание текста в абзаце без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Возвращает формат маркера абзаца. Только чтение [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Возвращает формат части по умолчанию абзаца. Наследование не применяется. Только чтение [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Возвращает или задаёт размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Возвращает или задаёт глубину абзаца. Значение 0 означает неопределённое значение. Чтение/запись Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли разрыв строки для восточноазиатского текста в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Возвращает или задаёт выравнивание шрифта в абзаце без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть задан отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Определяет, используется ли разрыв строки для латинского текста в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Возвращает или задаёт левый отступ в абзаце без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Возвращает или задаёт правый отступ в абзаце без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Возвращает или задаёт размер пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Возвращает или задаёт размер пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Возвращает или задаёт размер пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Возвращает табуляцию абзаца. Наследование не применяется. Только чтение [`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Получает эффективные данные форматирования абзаца с применённым наследованием. |

### Примечания

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Смотрите также

* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->