---
title: Contains
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine si la collection contient une valeur spécifique.
type: docs
weight: 60
url: /fr/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection.Contains method

Détermine si la collection contient une valeur spécifique.

```csharp
public bool Contains(IMathElement item)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| item | IMathElement | Objet à localiser dans la collection. |

### Return_Value

vrai si*item* se trouve dans la collection; sinon, faux.

### Exemples

Exemple :

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = collection.Contains(plusElement);
```

### Voir également

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* espace de noms [Aspose.Slides.MathText](../../imathelementcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
