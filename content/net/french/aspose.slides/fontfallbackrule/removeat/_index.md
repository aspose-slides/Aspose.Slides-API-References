---
title: RemoveAt
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime la police FallBack à lindex spécifié de la liste.
type: docs
weight: 100
url: /fr/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule.RemoveAt method

Supprime la police FallBack à l'index spécifié de la liste.

```csharp
public void RemoveAt(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro de la police à supprimer. |

### Exemples

```csharp
[C#]
// Créer une règle contient une liste de polices.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

//Suppression de Tahoma de la liste.
newRule.Remove (2);
```

### Voir également

* class [FontFallBackRule](../../fontfallbackrule)
* espace de noms [Aspose.Slides](../../fontfallbackrule)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
