---
title: AsArgumentOfFunction
second_title: Referencia de API de Aspose.Slides para .NET
description: Toma una función específica usando esta instancia como argumento
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Toma una función específica usando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parámetro    | Tipo        | Descripción     |
|--------------|-------------|------------------|
| functionName | IMathElement| Nombre de la función |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Véase también

* interfaz [IMathFunction](../../imathfunction)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Toma una función específica usando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parámetro    | Tipo    | Descripción     |
|--------------|---------|------------------|
| functionName | String  | Nombre de la función |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Véase también

* interfaz [IMathFunction](../../imathfunction)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Toma una función específica usando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parámetro    | Tipo                      | Descripción                                                  |
|--------------|---------------------------|-------------------------------------------------------------|
| functionType | MathFunctionsOfOneArgument| Uno de los tipos de función comunes de un argumento         |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Véase también

* interfaz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Toma una función específica usando esta instancia como argumento y un argumento adicional específico

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parámetro          | Tipo                           | Descripción                                                     |
|--------------------|--------------------------------|----------------------------------------------------------------|
| functionType       | MathFunctionsOfTwoArguments    | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument  | IMathElement                   | Argumento adicional dependiendo del tipo de función            |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase también

* interfaz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Toma una función específica usando esta instancia como argumento y un argumento adicional específico

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parámetro          | Tipo                           | Descripción                                                      |
|--------------------|--------------------------------|-----------------------------------------------------------------|
| functionType       | MathFunctionsOfTwoArguments    | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument  | String                         | Argumento adicional dependiendo del tipo de función             |

### Valor de retorno

Nuevo elemento matemático del tipo [`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Devuelve el logaritmo de 'x' en base '5'
```

### Véase también

* interfaz [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->