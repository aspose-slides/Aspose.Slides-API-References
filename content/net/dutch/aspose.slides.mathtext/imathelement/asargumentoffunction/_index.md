---
title: AsArgumentOfFunction
second_title: Aspose.Sildes voor .NET API-referentie
description: Neemt de opgegeven functie waarbij dit exemplaar als argument wordt gebruikt
type: docs
weight: 20
url: /nl/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Neemt de opgegeven functie die dit exemplaar als argument gebruikt

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | IMathElement | Functienaam |

### Retourwaarde

Nieuw wiskundig element van type [`IMathFunction`](../../imathfunction)

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Zie ook

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* naamruimte [Aspose.Slides.MathText](../../imathelement)
* assemblage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Neemt de opgegeven functie die dit exemplaar als argument gebruikt

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionName | String | Functienaam |

### Retourwaarde

Nieuw wiskundig element van type [`IMathFunction`](../../imathfunction)

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Zie ook

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* naamruimte [Aspose.Slides.MathText](../../imathelement)
* assemblage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Neemt de opgegeven functie die dit exemplaar als argument gebruikt

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Een van de veelvoorkomende functietypen met één argument |

### Retourwaarde

Nieuw wiskundig element van type [`IMathFunction`](../../imathfunction)

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Zie ook

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* naamruimte [Aspose.Slides.MathText](../../imathelement)
* assemblage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Neemt de opgegeven functie die dit exemplaar als argument gebruikt en een opgegeven extra argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Een van de veelvoorkomende functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Extra argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [`IMathFunction`](../../imathfunction)

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retourneert de logaritme van 'x' met grondtal '5'
```

### Zie ook

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* naamruimte [Aspose.Slides.MathText](../../imathelement)
* assemblage [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Neemt de opgegeven functie die dit exemplaar als argument gebruikt en een opgegeven extra argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Een van de veelvoorkomende functietypen met twee argumenten: Log, Lim, Min, Max |
| additionalArgument | String | Extra argument afhankelijk van het type functie |

### Retourwaarde

Nieuw wiskundig element van type [`IMathFunction`](../../imathfunction)

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retourneert de logaritme van 'x' met grondtal '5'
```

### Zie ook

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* naamruimte [Aspose.Slides.MathText](../../imathelement)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->