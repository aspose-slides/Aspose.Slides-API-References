---
title: ToLatex
second_title: Aspose.Sildes для .NET API Справочник
description: Получает математическое уравнение в формате LaTeX
type: docs
weight: 30
url: /ru/aspose.slides.mathtext/imathparagraph/tolatex/
---

## IMathParagraph.ToLatex метод

Получает математическое уравнение в формате LaTeX

```csharp
public string ToLatex()
```

### Примеры

Пример:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Add(new MathematicalText("a").Join("+").Join(new MathematicalText("b").Join("=").Join(new MathematicalText("c"))));
string mathLatex = mathParagraph.ToLatex();
```

### См. также

* интерфейс [IMathParagraph](../../imathparagraph)
* пространство имен [Aspose.Slides.MathText](../../imathparagraph)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->