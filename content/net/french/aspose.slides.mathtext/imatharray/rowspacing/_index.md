---
title: RowSpacing
second_title: Aspose.Sildes pour la référence de l'API .NET
description: Espacement entre les lignes d'un tableau. Il n'est utilisé que lorsque RowSpacingRule est défini sur 3. Exactement dans ce cas, l'unité de mesure est en points ou Multiple, dans ce cas l'unité de mesure est en demi-lignes. Par défaut  0
type: docs
weight: 60
url: /fr/aspose.slides.mathtext/imatharray/rowspacing/
---

## Propriété IMathArray.RowSpacing

Espacement entre les lignes d'un tableau. Il n'est utilisé que lorsque RowSpacingRule est défini sur 3. Exactement dans ce cas, l'unité de mesure est en points ou Multiple, dans ce cas l'unité de mesure est en demi-lignes. Par défaut : 0

```csharp
public uint RowSpacing { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.RowSpacingRule = MathRowSpacingRule.Exactly;
mathArray.RowSpacing = 10;
```

### Voir aussi

* interface [IMathArray](../../imatharray)
* namespace [Aspose.Slides.MathText](../../imatharray)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->