---
title: ExplicitBreak
second_title: Référence de l'API Aspose.Slides pour .NET
description: Explicit break spécifie sil y a un saut de ligne au début de lobjet Box de telle sorte que la ligne se termine au début de lobjet box. Spécifie le numéro de lopérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point dalignement pour la ligne courante du texte mathématique valeurs possibles  1..255 Par défaut  0 pas de saut explicite
type: docs
weight: 50
url: /fr/aspose.slides.mathtext/mathbox/explicitbreak/
---
## MathBox.ExplicitBreak property

Explicit break spécifie s'il y a un saut de ligne au début de l'objet Box, de telle sorte que la ligne se termine au début de l'objet box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne courante du texte mathématique valeurs possibles : 1..255 Par défaut : 0 (pas de saut explicite)

```csharp
public byte ExplicitBreak { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.ExplicitBreak = 1;
```

### Voir également

* class [MathBox](../../mathbox)
* espace de noms [Aspose.Slides.MathText](../../mathbox)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
