---
title: RemoveAt
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Supprime la police FallBack à l'index spécifié de la liste.
type: docs
weight: 100
url: /fr/aspose.slides/fontfallbackrule/removeat/
---

## Méthode FontFallBackRule.RemoveAt

Supprime la police FallBack à l'index spécifié de la liste.

```csharp
public void RemoveAt(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro de la police à supprimer. |

### Exemples

```csharp
[C#]
// Crée une règle contenant une liste de polices.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Suppression de Tahoma de la liste.
newRule.Remove (2);
```

### Voir aussi

* classe [FontFallBackRule](../../fontfallbackrule)
* espace de noms [Aspose.Slides](../../fontfallbackrule)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->