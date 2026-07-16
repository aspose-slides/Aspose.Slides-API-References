---
title: ToArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée et renvoie un tableau contenant toutes les polices de secours pour cette règle.
type: docs
weight: 105
url: /fr/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() méthode


Crée et renvoie un tableau contenant toutes les polices de secours pour cette règle.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Valeur de retour

Array of [System::String](../../../system/string/)
## Remarques



```cpp
// Créer une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtenir tous les noms de police sous forme de tableau
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) méthode


Crée et renvoie un tableau contenant toutes les polices de secours à partir de la plage spécifiée dans la liste.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice de la première police à ajouter. |
| count | **int32_t** | Un nombre de polices à ajouter. |

### Valeur de retour

Array of [System::String](../../../system/string/)
## Remarques



```cpp
// Créer une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtenir les deux derniers noms de police sous forme de tableau
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)