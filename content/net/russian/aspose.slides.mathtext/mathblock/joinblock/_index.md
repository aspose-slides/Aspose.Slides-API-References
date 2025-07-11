---
title: JoinBlock
second_title: Aspose.Sildes для .NET API Reference
description: Объединяет другой математический блок с этим
type: docs
weight: 150
url: /ru/aspose.slides.mathtext/mathblock/joinblock/
---

## MathBlock.JoinBlock метод

Объединяет другой математический блок с этим

```csharp
public IMathBlock JoinBlock(IMathBlock other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IMathBlock | Объединяемый блок |

### Возврат Значения

этот математический блок после объединения

### Примеры

Пример:

```csharp
[C#]
IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).Join(new MathematicalText("="));
IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).Join(new MathematicalText("+"))
.Join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
IMathBlock block3 = block1.JoinBlock(block2);
```

### См. также

* interface [IMathBlock](../../imathblock)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->