---
title: Accent
second_title: Référence API Aspose.Slides pour .NET
description: Définit un accent sur ce caractère au-dessus de cet élément
type: docs
weight: 10
url: /fr/aspose.slides.mathtext/mathelementbase/accent/
---

## Méthode MathElementBase.Accent

Définit un accent (un caractère au-dessus de cet élément)

```csharp
public IMathAccent Accent(char accentCharacter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| accentCharacter | Char | Caractère d'accent. La valeur doit être dans la plage de (U+0300–U+036F) ou (U+20D0–U+20EF) |

### Valeur de retour

Nouvelle instance de type [`IMathAccent`](../../imathaccent)

### Exemples

Exemple:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### Voir aussi

* interface [IMathAccent](../../imathaccent)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
