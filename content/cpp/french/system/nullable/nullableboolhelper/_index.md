---
title: NullableBoolHelper()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fonction d'aide pour vérifier si this et other sont tous deux non nuls et appeler une lambda le cas échéant. Utilisée dans les implémentations.
type: docs
weight: 105
url: /fr/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Fonction auxiliaire pour vérifier si **this** et **other** sont tous deux non nuls et appeler une lambda le cas échéant. Utilisée dans les implémentations.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Autre type nullable. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | Autre valeur nullable à comparer. |
| f | const std::function\<**bool**()>\& | Lambda à appeler si **this** et **other** ne sont pas nuls. |
| default_if_both_are_null | **bool** | Valeur de retour si les deux valeurs sont nulles. |

### Valeur de retour

false si **this** ou **other** est nul ; **default_if_both_are_null** si les deux sont nuls ; résultat de l'appel de **f** si les deux ne sont pas nuls.

## Voir aussi

* Classe [Nullable](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)