---
title: AsArgumentOfFunction
second_title: Aspose.Sildes dla .NET – Referencja API
description: Przyjmuje określoną funkcję, używając tej instancji jako argumentu
type: docs
weight: 20
url: /pl/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | IMathElement | Nazwa funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* interfejs [IMathElement](../../imathelement)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | String | Nazwa funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Przyjmuje określoną funkcję, używając tej instancji jako argumentu

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Jedna z typowych funkcji jednego argumentu |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowy określony argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jedna z powszechnych funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Zwraca logarytm 'x' o podstawie '5'
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfejs [IMathElement](../../imathelement)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowy określony argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jedna z powszechnych funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | String | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Zwraca logarytm 'x' o podstawie '5'
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->