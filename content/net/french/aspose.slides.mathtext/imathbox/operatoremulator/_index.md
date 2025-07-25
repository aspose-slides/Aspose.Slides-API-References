---
title: OperatorEmulator
second_title: Référence API Aspose.Slides pour .NET
description: Émulateur d'opérateurs. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie par exemple que le caractère peut servir de point pour un saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateurs sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur tel que . Valeur par défaut  faux
type: docs
weight: 70
url: /fr/aspose.slides.mathtext/imathbox/operatoremulator/
---

## IMathBox.OperatorEmulator propriété

Émulateur d'opérateurs. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point pour un saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateurs sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, tel que '=='. Valeur par défaut : faux

```csharp
public bool OperatorEmulator { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.OperatorEmulator = true;
```

### Voir aussi

* interface [IMathBox](../../imathbox)
* namespace [Aspose.Slides.MathText](../../imathbox)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->