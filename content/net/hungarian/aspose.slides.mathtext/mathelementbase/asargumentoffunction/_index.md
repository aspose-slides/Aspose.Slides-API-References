---
title: AsArgumentOfFunction
second_title: Aspose.Sildes .NET API referencia
description: Megadott függvényt vesz, amely ezt a példányt argumentumként használ
type: docs
weight: 20
url: /hu/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Megadott függvényt veszi, amely ezt a példányt argumentumként használ

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | IMathElement | Függvény neve |

### Visszatérési érték

Új matematikai elem típusa [`IMathFunction`](../../imathfunction)

### Példák

Példa:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Lásd még

* interfész [IMathFunction](../../imathfunction)
* interfész [IMathElement](../../imathelement)
* osztály [MathElementBase](../../mathelementbase)
* névtér [Aspose.Slides.MathText](../../mathelementbase)
* összeállítás [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Megadott függvényt veszi, amely ezt a példányt argumentumként használ

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | String | Függvény neve |

### Visszatérési érték

Új matematikai elem típusa [`IMathFunction`](../../imathfunction)

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Lásd még

* interfész [IMathFunction](../../imathfunction)
* osztály [MathElementBase](../../mathelementbase)
* névtér [Aspose.Slides.MathText](../../mathelementbase)
* összeállítás [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Megadott függvényt veszi, amely ezt a példányt argumentumként használ

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Egy közös egyargumentumos függvénytípus |

### Visszatérési érték

Új matematikai elem típusa [`IMathFunction`](../../imathfunction)

### Példák

Példa:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Lásd még

* interfész [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* osztály [MathElementBase](../../mathelementbase)
* névtér [Aspose.Slides.MathText](../../mathelementbase)
* összeállítás [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Megadott függvényt veszi, amely ezt a példányt argumentumként használ, valamint egy további argumentumot

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Két argumentumos közös függvénytípus: Log, Lim, Min, Max |
| additionalArgument | IMathElement | További argumentum a függvény típusától függően |

### Visszatérési érték

Új matematikai elem típusa [`IMathFunction`](../../imathfunction)

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Visszaadja az 'x' logaritmusát az '5' alapra
```

### Lásd még

* interfész [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfész [IMathElement](../../imathelement)
* osztály [MathElementBase](../../mathelementbase)
* névtér [Aspose.Slides.MathText](../../mathelementbase)
* összeállítás [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Megadott függvényt veszi, amely ezt a példányt argumentumként használ, valamint egy további argumentumot

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Két argumentumos közös függvénytípus: Log, Lim, Min, Max |
| additionalArgument | String | További argumentum a függvény típusától függően |

### Visszatérési érték

Új matematikai elem típusa [`IMathFunction`](../../imathfunction)

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja 'x' logaritmusát az '5' alapra
```

### Lásd még

* interfész [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* osztály [MathElementBase](../../mathelementbase)
* névtér [Aspose.Slides.MathText](../../mathelementbase)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->