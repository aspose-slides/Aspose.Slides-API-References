---
title: IParagraphFormat
second_title: Aspose.Sildes для .NET API Справочник
description: Этот класс содержит свойства форматирования абзацев. В отличие от IParagraphFormatEffectiveData./iparagraphformateffectivedata, все свойства этого класса могут быть изменены.
type: docs
weight: 6390
url: /ru/aspose.slides/iparagraphformat/
---

## Интерфейс IParagraphFormat

Этот класс содержит свойства форматирования абзацев. В отличие от [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), все свойства этого класса могут быть изменены.

```csharp
public interface IParagraphFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Возвращает или устанавливает выравнивание текста в абзаце без наследования. Чтение/запись [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Возвращает формат маркера абзаца. Только для чтения [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Возвращает формат по умолчанию для порции абзаца. Наследование не применяется. Только для чтения [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Возвращает или устанавливает размер табуляции по умолчанию без наследования. Чтение/запись Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Возвращает или устанавливает глубину абзаца. Значение 0 означает неопределенное значение. Чтение/запись Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Определяет, используется ли разрыв строки восточноазиатских языков в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Возвращает или устанавливает выравнивание шрифта в абзаце без наследования. Чтение/запись [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Определяет, используется ли подвешенная пунктуация в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Возвращает или устанавливает отступ первой строки/подвешенный отступ абзаца без наследования. Подвешенный отступ можно задать отрицательными значениями. Чтение/запись Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Определяет, используется ли разрыв строки латиницы в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Возвращает или устанавливает левый отступ в абзаце без наследования. Чтение/запись Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Возвращает или устанавливает правый отступ в абзаце без наследования. Чтение/запись Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Возвращает или устанавливает количество пространства после последней строки в абзаце без наследования. Положительное значение указывает на процент от размера шрифта, который должен составлять белый пробел. Отрицательное значение указывает размер белого пробела в пунктах. Чтение/запись Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Возвращает или устанавливает количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает на процент от размера шрифта, который должен составлять белый пробел. Отрицательное значение указывает размер белого пробела в пунктах. Чтение/запись Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Возвращает или устанавливает количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное - размер в пунктах. Наследование не применяется. Чтение/запись Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [`ITabCollection`](../itabcollection). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Получает данные форматирования абзаца с примененным наследованием. |

### Замечания

Этот класс используется для возврата и изменения свойств форматирования абзацев, определенных для конкретного абзаца. Это означает, что наследование не применяется при получении значений, поэтому в большинстве случаев вы получите значения, означающие "неопределено".

Чтобы получить значения параметров эффективного форматирования, включая унаследованные, вам необходимо использовать метод [`GetEffective`](./geteffective), который возвращает экземпляр [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### См. также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->