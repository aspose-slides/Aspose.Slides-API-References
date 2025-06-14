---
title: IMathFunction
second_title: Aspose.Slides pour .NET Référence API
description: Spécifie une fonction d'un argument.
type: docs
weight: 8020
url: /fr/aspose.slides.mathtext/imathfunction/
---

## Interface IMathFunction

Spécifie une fonction d'un argument.

```csharp
public interface IMathFunction : IMathElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathfunction/asimathelement) { get; } | Permet d'obtenir l'interface de base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathfunction/base) { get; } | Argument de la fonction |
| [Name](../../aspose.slides.mathtext/imathfunction/name) { get; } | Nom de la fonction Par exemple, les noms de fonctions sont sin et cos |

### Exemples

Exemple :

```csharp
[C#]
IMathFunction sinX = new MathematicalText("sin").Function("x");
```

### Voir Aussi

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->