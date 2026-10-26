---
title: AsArgumentOfFunction
second_title: Aspose.Sildes pro .NET API Reference
description: Přebírá určenou funkci s touto instancí jako argument
type: docs
weight: 20
url: /cs/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Přebírá určenou funkci s touto instancí jako argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | IMathElement | Název funkce |

### Návratová hodnota

New math element of type [`IMathFunction`](../../imathfunction)

### Příklady

Příklad:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Viz také

* rozhraní [IMathFunction](../../imathfunction)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestava [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Přebírá určenou funkci s touto instancí jako argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionName | String | Název funkce |

### Návratová hodnota

New math element of type [`IMathFunction`](../../imathfunction)

### Příklady

Příklad:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Viz také

* rozhraní [IMathFunction](../../imathfunction)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestava [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Přebírá určenou funkci s touto instancí jako argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Jeden ze společných typů funkcí s jedním argumentem |

### Návratová hodnota

New math element of type [`IMathFunction`](../../imathfunction)

### Příklady

Příklad:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Viz také

* rozhraní [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestava [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Přebírá určenou funkci s touto instancí jako argument a určený další argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jeden ze společných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Další argument v závislosti na typu funkce |

### Návratová hodnota

New math element of type [`IMathFunction`](../../imathfunction)

### Příklady

Příklad:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Vrací logaritmus 'x' se základem '5'
```

### Viz také

* rozhraní [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestava [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Přebírá určenou funkci s touto instancí jako argument a určený další argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jeden ze společných typů funkcí se dvěma argumenty: Log, Lim, Min, Max |
| additionalArgument | String | Další argument v závislosti na typu funkce |

### Návratová hodnota

New math element of type [`IMathFunction`](../../imathfunction)

### Příklady

Příklad:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Vrací logaritmus 'x' se základem '5'
```

### Viz také

* rozhraní [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestava [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->