---
title: AsArgumentOfFunction
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Używa określonej funkcji, przekazując tę instancję jako argument
type: docs
weight: 20
url: /pl/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Używa określonej funkcji, przekazując tę instancję jako argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* interfejs [IMathElement](../../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../imathelement)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Używa określonej funkcji, przekazując tę instancję jako argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionName | String | Function name |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* interfejs [IMathElement](../../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../imathelement)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Używa określonej funkcji, przekazując tę instancję jako argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Jedna z typowych funkcji jednego argumentu |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interfejs [IMathElement](../../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../imathelement)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Używa określonej funkcji, przekazując tę instancję jako argument oraz dodatkowy argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jedna z typowych funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Zwraca logarytm z 'x' o podstawie '5'
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfejs [IMathElement](../../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../imathelement)
* zestaw [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Używa określonej funkcji, przekazując tę instancję jako argument oraz dodatkowy argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Jedna z typowych funkcji dwóch argumentów: Log, Lim, Min, Max |
| additionalArgument | String | Dodatkowy argument zależny od typu funkcji |

### Wartość zwracana

Nowy element matematyczny typu [`IMathFunction`](../../imathfunction)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Zwraca logarytm z 'x' o podstawie '5'
```

### Zobacz także

* interfejs [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfejs [IMathElement](../../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../imathelement)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->