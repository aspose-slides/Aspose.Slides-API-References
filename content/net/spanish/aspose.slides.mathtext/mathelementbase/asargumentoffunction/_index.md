---
title: AsArgumentOfFunction
second_title: Referencia de la API de Aspose.Slides para .NET
description: Toma una función especificada utilizando esta instancia como argumento
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Toma una función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | IMathElement | Nombre de la función |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Véase también

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Toma una función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | String | Nombre de la función |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Véase también

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Toma una función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Uno de los tipos de función comunes de un argumento |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Véase también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Toma una función especificada utilizando esta instancia como argumento y un argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argumento adicional dependiendo del tipo de la función |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Toma una función especificada utilizando esta instancia como argumento y un argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | String | Argumento adicional dependiendo del tipo de la función |

### Valor de retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->