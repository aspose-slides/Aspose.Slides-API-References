---
title: AsArgumentOfFunction
second_title: Référence de l'API Aspose.Slides pour .NET
description: Prend une fonction spécifiée en utilisant cette instance comme argument
type: docs
weight: 20
url: /fr/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---

## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Prend une fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | IMathElement | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Prend une fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | String | Nom de la fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Prend une fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Un des types de fonctions courantes à un argument |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Prend une fonction spécifiée en utilisant cette instance comme argument et un argument additionnel spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Un des types de fonctions courantes à deux arguments : Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argument additionnel selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retourne le logarithme de 'x' à la base '5'
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Prend une fonction spécifiée en utilisant cette instance comme argument et un argument additionnel spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Un des types de fonctions courantes à deux arguments : Log, Lim, Min, Max |
| additionalArgument | String | Argument additionnel selon le type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retourne le logarithme de 'x' à la base '5'
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->