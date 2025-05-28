---
title: AsArgumentOfFunction
second_title: Aspose.Slides für .NET-API-Referenz
description: Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument
type: docs
weight: 20
url: /de/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | IMathElement | Funktionsname |

### Rückgabewert

Neues mathematisches Element des Typs[`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Siehe auch

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionName | String | Funktionsname |

### Rückgabewert

Neues mathematisches Element des Typs[`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Siehe auch

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Einer der häufigsten Funktionstypen eines Arguments |

### Rückgabewert

Neues mathematisches Element des Typs[`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Siehe auch

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Akzeptiert die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Einer der häufigsten Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Zusätzliches Argument je nach Art der Funktion |

### Rückgabewert

Neues mathematisches Element des Typs[`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

### Siehe auch

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Akzeptiert die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Einer der häufigsten Funktionstypen mit zwei Argumenten: Log, Lim, Min, Max |
| additionalArgument | String | Zusätzliches Argument je nach Art der Funktion |

### Rückgabewert

Neues mathematisches Element des Typs[`IMathFunction`](../../imathfunction)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Gibt den Logarithmus von 'x' zur Basis '5' zurück
```

### Siehe auch

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
