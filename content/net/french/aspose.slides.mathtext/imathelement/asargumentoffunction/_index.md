---
title: AsArgumentOfFunction
second_title: Référence de l'API Aspose.Slides pour .NET
description: Prend la fonction spécifiée en utilisant cette instance comme argument
type: docs
weight: 20
url: /fr/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Prend la fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| functionName | IMathElement | Nom de la fonction |

### Return_Value

Nouvel élément mathématique de type[`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Voir également

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Prend la fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| functionName | String | Nom de la fonction |

### Return_Value

Nouvel élément mathématique de type[`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Voir également

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Prend la fonction spécifiée en utilisant cette instance comme argument

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | L'un des types de fonction communs d'un argument |

### Return_Value

Nouvel élément mathématique de type[`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Voir également

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | L'un des types de fonction communs à deux arguments : Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argument supplémentaire selon le type de fonction |

### Return_Value

Nouvel élément mathématique de type[`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Renvoie le logarithme de 'x' en base '5'
```

### Voir également

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | L'un des types de fonction communs à deux arguments : Log, Lim, Min, Max |
| additionalArgument | String | Argument supplémentaire selon le type de fonction |

### Return_Value

Nouvel élément mathématique de type[`IMathFunction`](../../imathfunction)

### Exemples

Exemple :

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Renvoie le logarithme de 'x' en base '5'
```

### Voir également

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
