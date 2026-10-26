---
title: CheckDiffForAny()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie qu'un élément de la collection satisfait le prédicat.
type: docs
weight: 27
url: /fr/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) méthode

Vérifie qu'un élément de la collection satisfait le prédicat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Prédicat à vérifier. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valeurs à vérifier. |

### Valeur de retour

Vrai si la vérification réussit pour un élément, faux si tous réussissent.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Structure [CollectionAssertHelper](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)