---
title: IMathAccent
second_title: Aspose.Sildes для .NET API Reference
description: Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака Пример ́
type: docs
weight: 7830
url: /ru/aspose.slides.mathtext/imathaccent/
---

## Интерфейс IMathAccent

Указывает функцию акцента, состоящую из основы и комбинирующего диакритического знака Пример: 𝑎́

```csharp
public interface IMathAccent : IMathElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathaccent/asimathelement) { get; } | Позволяет получить базовый интерфейс IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathaccent/base) { get; } | Аргумент, к которому был применен акцент |
| [Character](../../aspose.slides.mathtext/imathaccent/character) { get; set; } | Символ акцента Значение должно быть в диапазоне (U+0300–U+036F) или (U+20D0–U+20EF) Значение по умолчанию: комбинированный циркумфлексный акцент (U+0302) |

### Примеры

Пример:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### См. также

* интерфейс [IMathElement](../imathelement)
* пространство имен [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: создано xmldocmd для Aspose.Slides.dll -->