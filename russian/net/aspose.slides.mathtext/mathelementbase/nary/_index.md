---
title: Nary
second_title: Справочник по API Aspose.Slides для .NET
description: Создает N-арный оператор
type: docs
weight: 90
url: /ru/net/aspose.slides.mathtext/mathelementbase/nary/
---
## Nary(MathNaryOperatorTypes, IMathElement, IMathElement) {#nary}

Создает N-арный оператор

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | MathNaryOperatorTypes | N-арный тип оператора |
| lowerLimit | IMathElement | Нижний предел |
| upperLimit | IMathElement | Верхний предел |

### Возвращаемое значение

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("i-1");
IMathElement lowerLimit = new MathematicalText("i=0");
IMathElement upperLimit = new MathematicalText("𝑛");
IMathNaryOperator naryOperator = baseElement.Nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## Nary(MathNaryOperatorTypes, string, string) {#nary_1}

Создает N-арный оператор

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, string lowerLimit, string upperLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | MathNaryOperatorTypes | N-арный тип оператора |
| lowerLimit | String | Нижний предел |
| upperLimit | String | Верхний предел |

### Возвращаемое значение

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("i").Nary(MathNaryOperatorTypes.Summation, "i=0", "𝑛");
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->