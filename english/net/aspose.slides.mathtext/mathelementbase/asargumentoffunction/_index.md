---
title: AsArgumentOfFunction
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase.AsArgumentOfFunction method (1 of 5)

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | IMathElement | Function name |

## Return Value

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

## MathElementBase.AsArgumentOfFunction method (2 of 5)

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | String | Function name |

## Return Value

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

## MathElementBase.AsArgumentOfFunction method (3 of 5)

Takes specified function using this instance as the argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | One of the common function type of one argument |

## Return Value

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

## MathElementBase.AsArgumentOfFunction method (4 of 5)

Takes specified function using this instance as the argument and specified additional argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Additional argument depending on the type of function |

## Return Value

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

## MathElementBase.AsArgumentOfFunction method (5 of 5)

Takes specified function using this instance as the argument and specified additional argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | String | Additional argument depending on the type of function |

## Return Value

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
