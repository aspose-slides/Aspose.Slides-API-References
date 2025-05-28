---
title: IParagraphFormat
second_title: Aspose.Slides для .NET API Справочник
description: Этот класс содержит свойства форматирования параграфов. В отличие от IParagraphFormatEffectiveData./iparagraphformateffectivedata, все свойства этого класса доступны для записи.
type: docs
weight: 6390
url: /ru/aspose.slides/iparagraphformat/
---

## Интерфейс IParagraphFormat

Этот класс содержит свойства форматирования параграфов. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса доступны для записи.

```csharp
public interface IParagraphFormat
```

## Свойства

| Название | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Возвращает или задает выравнивание текста в параграфе без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Возвращает формат маркера параграфа. Только для чтения [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Возвращает формат части по умолчанию для параграфа. Наследование не применяется. Только для чтения [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Возвращает или задает размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Возвращает или задает глубину параграфа. Значение 0 означает неопределенное значение. Чтение/запись Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Определяет, будет ли применяться разрыв строки для восточноазиатских языков в параграфе. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Возвращает или задает выравнивание шрифта в параграфе без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Определяет, будет ли применяться висячая пунктуация в параграфе. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Возвращает или задает отступ первой строки/висячий отступ параграфа без наследования. Висячий отступ может быть определен отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Определяет, будет ли применяться разрыв строки для латиницы в параграфе. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Возвращает или задает левый отступ в параграфе без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Возвращает или задает правый отступ в параграфе без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Определяет, будет ли применяться правостороннее написание в параграфе. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Возвращает или задает количество пробела после последней строки в параграфе без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять белый промежуток. Отрицательное значение указывает размер белого промежутка в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Возвращает или задает количество пробела перед первой строкой в параграфе без наследования. Положительное значение указывает процент от размера шрифта, который должен составлять белый промежуток. Отрицательное значение указывает размер белого промежутка в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Возвращает или задает количество пробела между базовыми строками в параграфе. Положительное значение означает процент, отрицательное - размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Возвращает табуляции параграфа. Наследование не применяется. Только для чтения [`ITabCollection`](../itabcollection). |

## Методы

| Название | Описание |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Получает данные о форматировании параграфа с учетом применённого наследования. |

### Примечания

Этот класс используется для возврата и изменения свойств форматирования параграфов, определённых для конкретного параграфа. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределенно".

Чтобы получить значения эффективных параметров форматирования, включая унаследованные, вам необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->