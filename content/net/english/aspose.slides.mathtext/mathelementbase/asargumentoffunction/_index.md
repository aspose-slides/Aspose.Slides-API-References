---
title: AsArgumentOfFunction
second_title: Aspose.Sildes for .NET API Reference
description: Takes specified function using this instance as the argument
type: docs
weight: 20
url: /aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Return Value

New math element of type [`IMathFunction`](../../imathfunction)

### Examples

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### See Also

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | String | Function name |

### Return Value

New math element of type [`IMathFunction`](../../imathfunction)

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### See Also

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | One of the common function type of one argument |

### Return Value

New math element of type [`IMathFunction`](../../imathfunction)

### Examples

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### See Also

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Takes specified function using this instance as the argument and specified additional argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Additional argument depending on the type of function |

### Return Value

New math element of type [`IMathFunction`](../../imathfunction)

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returns the logarithm of 'x' to the base '5'
```

### See Also

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Takes specified function using this instance as the argument and specified additional argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | String | Additional argument depending on the type of function |

### Return Value

New math element of type [`IMathFunction`](../../imathfunction)

### Examples

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returns the logarithm of 'x' to the base '5'
```

### See Also

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
