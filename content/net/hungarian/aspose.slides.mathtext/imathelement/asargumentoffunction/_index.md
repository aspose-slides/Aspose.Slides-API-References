---
title: AsArgumentOfFunction
second_title: Aspose.Sildes .NET API referencia
description: A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként
type: docs
weight: 20
url: /hu/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Visszatérési érték

Új matematikai elem a(z) [`IMathFunction`](../../imathfunction) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Lásd még

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | String | Function name |

### Visszatérési érték

Új matematikai elem a(z) [`IMathFunction`](../../imathfunction) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Lásd még

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | A közös egy argumentumos függvénytípusok egyike |

### Visszatérési érték

Új matematikai elem a(z) [`IMathFunction`](../../imathfunction) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Lásd még

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként, és egy további argumentumot ad meg

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | A közös két argumentumos függvénytípusok egyike: Log, Lim, Min, Max |
| additionalArgument | IMathElement | A függvénytípustól függő további argumentum |

### Visszatérési érték

Új matematikai elem a(z) [`IMathFunction`](../../imathfunction) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Visszaadja az 'x' logaritmusát a '5' alapra
```

### Lásd még

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

A megadott függvényt úgy veszi, hogy ezt a példányt használja argumentumként, és egy további argumentumot ad meg

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | A közös két argumentumos függvénytípusok egyike: Log, Lim, Min, Max |
| additionalArgument | String | A függvénytípustól függő további argumentum |

### Visszatérési érték

Új matematikai elem a(z) [`IMathFunction`](../../imathfunction) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Visszaadja az 'x' logaritmusát a '5' alapra
```

### Lásd még

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->