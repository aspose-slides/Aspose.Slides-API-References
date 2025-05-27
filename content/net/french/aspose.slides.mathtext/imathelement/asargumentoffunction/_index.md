---
title: EnArgumentDeFonction
second_title: Référence de l'API Aspose.Slides pour .NET
description: Prend la fonction spécifiée en utilisant cette instance comme argument
type: docs
weight: 20
url: /fr/aspose.slides.mathtext/imathelement/asargumentoffunction/
---

## EnArgumentDeFonction(IMathElement) {#asargumentoffunction}

Prend la fonction spécifiée en utilisant cette instance comme argument

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
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## EnArgumentDeFonction(string) {#asargumentoffunction_4}

Prend la fonction spécifiée en utilisant cette instance comme argument

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
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## EnArgumentDeFonction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Prend la fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | L'un des types de fonction courants d'un argument |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## EnArgumentDeFonction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | L'un des types de fonctions courants de deux arguments : Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argument supplémentaire en fonction du type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Renvoie le logarithme de 'x' à la base '5'
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## EnArgumentDeFonction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | L'un des types de fonctions courants de deux arguments : Log, Lim, Min, Max |
| additionalArgument | String | Argument supplémentaire en fonction du type de fonction |

### Valeur de retour

Nouvel élément mathématique de type [`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Renvoie le logarithme de 'x' à la base '5'
```

### Voir aussi

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->