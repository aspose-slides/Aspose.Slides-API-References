---
title: IndexOf()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'indice de la règle spécifiée dans la collection.
type: docs
weight: 118
url: /fr/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) method


Renvoie l'indice de la règle spécifiée dans la collection.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nom de la police à rechercher. |

### Return Value

Indice d'une police ou -1 si la police n'est pas trouvée dans la liste.
## Remarques



```cpp
// Crée une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtenir l'indice de Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)