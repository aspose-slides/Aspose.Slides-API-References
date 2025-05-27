---
title: BaseJustification
second_title: Aspose.Slides pour .NET Référence de l'API
description: Spécifie l'alignement de l'array par rapport au texte environnant. Le texte en dehors de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. Valeur par défaut : Centre
type: docs
weight: 30
url: /fr/aspose.slides.mathtext/imatharray/basejustification/
---

## Propriété IMathArray.BaseJustification

Spécifie l'alignement de l'array par rapport au texte environnant. Le texte en dehors de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. Valeur par défaut : Centre

```csharp
public MathVerticalAlignment BaseJustification { get; set; }
```

### Exemples

Exemple :
 
```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.BaseJustification = MathVerticalAlignment.Top;
```

### Voir aussi

* enum [MathVerticalAlignment](../../mathverticalalignment)
* interface [IMathArray](../../imatharray)
* namespace [Aspose.Slides.MathText](../../imatharray)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->