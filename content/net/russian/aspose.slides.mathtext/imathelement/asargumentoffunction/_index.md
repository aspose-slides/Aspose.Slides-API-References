---
title: AsArgumentOfFunction
second_title: Справочник по API Aspose.Slides для .NET
description: Принимает указанную функцию используя этот экземпляр в качестве аргумента
type: docs
weight: 20
url: /ru/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | IMathElement | Функция name |

### Возвращаемое значение

Новый математический элемент типа[`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Смотрите также

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | String | Функция name |

### Возвращаемое значение

Новый математический элемент типа[`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Смотрите также

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Один общего типа функции одного аргумента |

### Возвращаемое значение

Новый математический элемент типа[`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Смотрите также

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Один из общих типов функций с двумя аргументами:Log, Lim, Min, Max |
| additionalArgument | IMathElement | Дополнительный аргумент в зависимости от типа функции |

### Возвращаемое значение

Новый математический элемент типа[`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase);  // Возвращает логарифм 'x' по основанию '5'
```

### Смотрите также

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Один из общих типов функций с двумя аргументами:Log, Lim, Min, Max |
| additionalArgument | String | Дополнительный аргумент в зависимости от типа функции |

### Возвращаемое значение

Новый математический элемент типа[`IMathFunction`](../../imathfunction)

### Примеры

Пример:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5");  // Возвращает логарифм 'x' по основанию '5'
```

### Смотрите также

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
