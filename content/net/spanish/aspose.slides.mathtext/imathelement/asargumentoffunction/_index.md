---
title: AsArgumentOfFunction
second_title: Referencia de la API de Aspose.Slides para .NET
description: Toma la función especificada utilizando esta instancia como argumento
type: docs
weight: 20
url: /es/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Toma la función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| functionName | IMathElement | Nombre de la función |

### Valor_devuelto

Nuevo elemento matemático de tipo[`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Ver también

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Toma la función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| functionName | String | Nombre de la función |

### Valor_devuelto

Nuevo elemento matemático de tipo[`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Ver también

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Toma la función especificada utilizando esta instancia como argumento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Uno de los tipos de funciones comunes de un argumento. |

### Valor_devuelto

Nuevo elemento matemático de tipo[`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Ver también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de funciones comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argumento adicional dependiendo del tipo de función |

### Valor_devuelto

Nuevo elemento matemático de tipo[`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Devuelve el logaritmo de 'x' en base '5'
```

### Ver también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno de los tipos de funciones comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | String | Argumento adicional dependiendo del tipo de función |

### Valor_devuelto

Nuevo elemento matemático de tipo[`IMathFunction`](../../imathfunction)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Devuelve el logaritmo de 'x' en base '5'
```

### Ver también

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
