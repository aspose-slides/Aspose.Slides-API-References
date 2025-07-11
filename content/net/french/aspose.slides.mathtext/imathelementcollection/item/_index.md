---
title: Item
second_title: Aspose.Sildes pour .NET API Reference
description: Obtient l'élément à l'index spécifié. Lecture seule IMathElementaspose.slides.mathtext/imathelement.
type: docs
weight: 30
url: /fr/aspose.slides.mathtext/imathelementcollection/item/
---

## IMathElementCollection indexer

Obtient l'élément à l'index spécifié. Lecture seule [`IMathElement`](../../imathelement).

```csharp
public IMathElement this[int index] { get; }
```

| Paramètre | Description |
| --- | --- |
| index | L'index basé sur zéro de l'élément à obtenir |

### Exemples

Exemple:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### Voir Aussi

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* namespace [Aspose.Slides.MathText](../../imathelementcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
