---
title: AsArgumentOfFunction
second_title: Aspose.Sildes för .NET API-referens
description: Tar den specificerade funktionen och använder detta objekt som argument
type: docs
weight: 20
url: /sv/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Tar den specificerade funktionen och använder detta objekt som argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | IMathElement | Funktionsnamn |

### Returvärde

Nytt matematiskt element av typen [`IMathFunction`](../../imathfunction)

### Exempel

Exempel:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Se också

* gränssnitt [IMathFunction](../../imathfunction)
* gränssnitt [IMathElement](../../imathelement)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Tar den specificerade funktionen och använder detta objekt som argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionName | String | Funktionsnamn |

### Returvärde

Nytt matematiskt element av typen [`IMathFunction`](../../imathfunction)

### Exempel

Exempel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Se också

* gränssnitt [IMathFunction](../../imathfunction)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Tar den specificerade funktionen och använder detta objekt som argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | En av de vanliga funktionstyperna med ett argument |

### Returvärde

Nytt matematiskt element av typen [`IMathFunction`](../../imathfunction)

### Exempel

Exempel:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Se också

* gränssnitt [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Tar den specificerade funktionen och använder detta objekt som argument samt ett angivet extra argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Extra argument beroende på funktionstyp |

### Returvärde

Nytt matematiskt element av typen [`IMathFunction`](../../imathfunction)

### Exempel

Exempel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Returnerar logaritmen av 'x' till basen '5'
```

### Se också

* gränssnitt [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* gränssnitt [IMathElement](../../imathelement)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Tar den specificerade funktionen och använder detta objekt som argument samt ett angivet extra argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | En av de vanliga funktionstyperna med två argument: Log, Lim, Min, Max |
| additionalArgument | String | Extra argument beroende på funktionstyp |

### Returvärde

Nytt matematiskt element av typen [`IMathFunction`](../../imathfunction)

### Exempel

Exempel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Returnerar logaritmen av 'x' till basen '5'
```

### Se också

* gränssnitt [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->