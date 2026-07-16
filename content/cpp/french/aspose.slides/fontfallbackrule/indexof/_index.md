---
title: IndexOf()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'indice de la règle spécifiée dans la collection.
type: docs
weight: 157
url: /fr/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) méthode

Renvoie l'indice de la règle spécifiée dans la collection.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nom de la police à rechercher. |

### Valeur de retour

Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.

## Remarques

```cpp
// Créer une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtenir l'indice de Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)