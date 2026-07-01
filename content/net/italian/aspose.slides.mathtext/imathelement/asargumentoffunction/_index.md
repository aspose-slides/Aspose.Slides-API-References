---
title: AsArgumentOfFunction
second_title: Riferimento API Aspose.Sildes per .NET
description: Prende la funzione specificata usando questa istanza come argomento
type: docs
weight: 20
url: /it/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Prende la funzione specificata usando questa istanza come argomento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | IMathElement | Nome della funzione |

### Valore restituito

Nuovo elemento matematico di tipo [`IMathFunction`](../../imathfunction)

### Esempi

Esempio:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Vedi anche

* interfaccia [IMathFunction](../../imathfunction)
* interfaccia [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Prende la funzione specificata usando questa istanza come argomento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | String | Nome della funzione |

### Valore restituito

Nuovo elemento matematico di tipo [`IMathFunction`](../../imathfunction)

### Esempi

Esempio:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Vedi anche

* interfaccia [IMathFunction](../../imathfunction)
* interfaccia [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Prende la funzione specificata usando questa istanza come argomento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Uno dei tipi di funzione comuni con un argomento |

### Valore restituito

Nuovo elemento matematico di tipo [`IMathFunction`](../../imathfunction)

### Esempi

Esempio:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Vedi anche

* interfaccia [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interfaccia [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno dei tipi di funzione comuni con due argomenti: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore restituito

Nuovo elemento matematico di tipo [`IMathFunction`](../../imathfunction)

### Esempi

Esempio:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Restituisce il logaritmo di 'x' in base '5'
```

### Vedi anche

* interfaccia [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfaccia [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Uno dei tipi di funzione comuni con due argomenti: Log, Lim, Min, Max |
| additionalArgument | String | Argomento aggiuntivo a seconda del tipo di funzione |

### Valore restituito

Nuovo elemento matematico di tipo [`IMathFunction`](../../imathfunction)

### Esempi

Esempio:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Restituisce il logaritmo di 'x' in base '5'
```

### Vedi anche

* interfaccia [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interfaccia [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->