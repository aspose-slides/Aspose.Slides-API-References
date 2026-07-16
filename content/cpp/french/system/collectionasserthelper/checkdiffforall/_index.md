---
title: CheckDiffForAll()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie que tous les éléments de la collection respectent le prédicat.
type: docs
weight: 14
url: /fr/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) méthode


Vérifie que tous les éléments de la collection respectent le prédicat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Prédicat à vérifier. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valeurs à vérifier. |

### Valeur de retour

false si la vérification échoue pour un élément, true si tous passent.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Structure [CollectionAssertHelper](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)