---
title: MathBar
second_title: Aspose.Sildes для .NET API Справочник
description: Инициализирует MathBar с позицией над строкой верхняя позиция
type: docs
weight: 10
url: /ru/aspose.slides.mathtext/mathbar/mathbar/
---

## MathBar(IMathElement) {#constructor}

Инициализирует MathBar с над строкой (верхняя позиция)

```csharp
public MathBar(IMathElement element)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | IMathElement | Базовый элемент, к которому применяется линия |

### Примеры

Пример:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* класс [MathBar](../../mathbar)
* пространство имен [Aspose.Slides.MathText](../../mathbar)
* сборка [Aspose.Slides](../../../)

---

## MathBar(IMathElement, MathTopBotPositions) {#constructor_1}

Инициализирует MathBar с заданной позицией

```csharp
public MathBar(IMathElement element, MathTopBotPositions position)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | IMathElement | Базовый элемент, к которому применяется линия |
| position | MathTopBotPositions | Позиция линии бар |

### Примеры

Пример:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
```

### См. также

* интерфейс [IMathElement](../../imathelement)
* перечисление [MathTopBotPositions](../../mathtopbotpositions)
* класс [MathBar](../../mathbar)
* пространство имен [Aspose.Slides.MathText](../../mathbar)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->