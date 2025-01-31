---
title: MathParagraph
second_title: Справочник по API Aspose.Slides для .NET
description: Математический абзац являющийся контейнером для математических блоков IMathBlock
type: docs
weight: 8180
url: /ru/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph class

Математический абзац, являющийся контейнером для математических блоков (IMathBlock)

```csharp
public class MathParagraph : IMathParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MathParagraph](mathparagraph#constructor)() | Инициализирует новый экземпляр класса MathParagraph. |
| [MathParagraph](mathparagraph#constructor_1)(IMathBlock) | Инициализирует новый экземпляр класса MathParagraph. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathparagraph/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтенияInt32. |
| [Item](../../aspose.slides.mathtext/mathparagraph/item) { get; set; } | Получает элемент по указанному индексу. Только для чтения[`IMathBlock`](../imathblock). |
| [Justification](../../aspose.slides.mathtext/mathparagraph/justification) { get; set; } | Обоснование абзаца Значение по умолчанию:CenteredAsGroup |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.slides.mathtext/mathparagraph/add)(IMathBlock) | Добавляет IMathBlock в конец коллекции. |
| [Clear](../../aspose.slides.mathtext/mathparagraph/clear)() | Удаляет все элементы из коллекции. |
| [Contains](../../aspose.slides.mathtext/mathparagraph/contains)(IMathBlock) | Определяет, содержит ли коллекция определенное значение. |
| [IndexOf](../../aspose.slides.mathtext/mathparagraph/indexof)(IMathBlock) | Определяет индекс конкретного IMathBlock в коллекции. |
| [Insert](../../aspose.slides.mathtext/mathparagraph/insert)(int, IMathBlock) | Вставляет IMathBlock в коллекцию по указанному индексу. |
| [Remove](../../aspose.slides.mathtext/mathparagraph/remove)(IMathBlock) | Удаляет первое вхождение определенного объекта из коллекции/&gt;. |
| [RemoveAt](../../aspose.slides.mathtext/mathparagraph/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathparagraph/writeasmathml)(Stream) | Сохраняет содержимое этого[`MathParagraph`](../mathparagraph)как MathML |

### Примеры

Пример:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### Смотрите также

* interface [IMathParagraph](../imathparagraph)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
