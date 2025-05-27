---
title: AsArgumentOfFunction
second_title: Aspose.Sildes для .NET API Reference
description: Принимает заданную функцию, используя этот экземпляр в качестве аргумента
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Принимает заданную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | IMathElement | Имя функции |

### Возвращаемое значение

Новый математический элемент типа [`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### См. также

* интерфейс [IMathFunction](../../imathfunction)
* интерфейс [IMathElement](../../imathelement)
* класс [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Принимает заданную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | String | Имя функции |

### Возвращаемое значение

Новый математический элемент типа [`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### См. также

* интерфейс [IMathFunction](../../imathfunction)
* класс [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Принимает заданную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Один из распространенных типов функции с одним аргументом |

### Возвращаемое значение

Новый математический элемент типа [`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### См. также

* интерфейс [IMathFunction](../../imathfunction)
* перечисление [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* класс [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Принимает заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Один из распространенных типов функции с двумя аргументами: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Дополнительный аргумент в зависимости от типа функции |

### Возвращаемое значение

Новый математический элемент типа [`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Возвращает логарифм 'x' по основанию '5'
```

### См. также

* интерфейс [IMathFunction](../../imathfunction)
* перечисление [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* интерфейс [IMathElement](../../imathelement)
* класс [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Принимает заданную функцию, используя этот экземпляр в качестве аргумента и заданный дополнительный аргумент

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Один из распространенных типов функции с двумя аргументами: Log, Lim, Min, Max |
| additionalArgument | String | Дополнительный аргумент в зависимости от типа функции |

### Возвращаемое значение

Новый математический элемент типа [`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Возвращает логарифм 'x' по основанию '5'
```

### См. также

* интерфейс [IMathFunction](../../imathfunction)
* перечисление [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* класс [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->