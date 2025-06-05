---
title: AsArgumentOfFunction
second_title: Aspose.Slides für .NET API Referenz
description: Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument
type: docs
weight: 20
url: /de/aspose.slides.mathtext/imathelement/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | IMathElement | Funktionsname |

### Rückgabewert

Neues Mathematikelement vom Typ [`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Siehe Auch

* Schnittstelle [IMathFunction](../../imathfunction)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | String | Funktionsname |

### Rückgabewert

Neues Mathematikelement vom Typ [`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Siehe Auch

* Schnittstelle [IMathFunction](../../imathfunction)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Einer der gängigen Funktionstypen mit einem Argument |

### Rückgabewert

Neues Mathematikelement vom Typ [`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Siehe Auch

* Schnittstelle [IMathFunction](../../imathfunction)
* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Einer der gängigen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Zusätzliches Argument abhängig vom Typ der Funktion |

### Rückgabewert

Neues Mathematikelement vom Typ [`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

### Siehe Auch

* Schnittstelle [IMathFunction](../../imathfunction)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Einer der gängigen Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | String | Zusätzliches Argument abhängig vom Typ der Funktion |

### Rückgabewert

Neues Mathematikelement vom Typ [`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

### Siehe Auch

* Schnittstelle [IMathFunction](../../imathfunction)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->