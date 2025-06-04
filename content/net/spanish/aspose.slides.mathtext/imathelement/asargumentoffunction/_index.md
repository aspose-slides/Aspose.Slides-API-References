---
title: AsArgumentOfFunction
second_title: Referencia de API de Aspose.Slides para .NET
description: Toma la función especificada usando esta instancia como el argumento
type: docs
weight: 20
url: /es/aspose.slides.mathtext/imathelement/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Toma la función especificada usando esta instancia como el argumento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | IMathElement | Nombre de la función |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Véase También

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Toma la función especificada usando esta instancia como el argumento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | String | Nombre de la función |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Véase También

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Toma la función especificada usando esta instancia como el argumento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Uno de los tipos de función comunes de un argumento |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Véase También

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argumento adicional dependiendo del tipo de función |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase También

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | String | Argumento adicional dependiendo del tipo de función |

### Valor de Retorno

Nuevo elemento matemático de tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase También

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->