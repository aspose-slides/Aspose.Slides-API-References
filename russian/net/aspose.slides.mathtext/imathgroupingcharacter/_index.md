---
title: IMathGroupingCharacter
second_title: Справочник по API Aspose.Slides для .NET
description: Указывает символ группировки над или под выражением обычно для выделения связи между элементами
type: docs
weight: 7580
url: /ru/net/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter interface

Указывает символ группировки над или под выражением, обычно для выделения связи между элементами

```csharp
public interface IMathGroupingCharacter : IMathElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathgroupingcharacter/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathgroupingcharacter/base) { get; } | Базовый аргумент |
| [Character](../../aspose.slides.mathtext/imathgroupingcharacter/character) { get; set; } | Символ группировки Значение по умолчанию:U+23DF (НИЖНЯЯ КРУПНАЯ СКОБКА) |
| [Position](../../aspose.slides.mathtext/imathgroupingcharacter/position) { get; set; } | Позиция группирующего символа. По умолчанию:Низ |
| [VerticalJustification](../../aspose.slides.mathtext/imathgroupingcharacter/verticaljustification) { get; set; } | Вертикальное выравнивание группового символа. Задает выравнивание объекта относительно базовой линии. Например, когда символ группы находится над объектом, Вертикальное выравнивание по верху означает, что верх объекта падает на базовую линию; когда для параметра VerticalJustification установлено значение Bottom, нижняя часть объекта находится на базовой линии По умолчанию:Bottom для Position=Top и Top для Position=Bottom |

### Примеры

Пример:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Смотрите также

* interface [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->