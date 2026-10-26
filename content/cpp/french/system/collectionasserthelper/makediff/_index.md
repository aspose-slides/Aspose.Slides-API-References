---
title: MakeDiff()
second_title: Référence API Aspose.Slides pour C++
description: Calcule le 'diff' entre deux collections. Pour chaque élément de chaque collection en tant que clé, la valeur résultante sera positive si l'élément apparaît plus souvent dans la collection \"expected\", négative s'il apparaît plus souvent dans la collection \"actual\", et zéro s'il apparaît le même nombre de fois dans chaque collection.
type: docs
weight: 1
url: /fr/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) méthode

Calcule le « diff » entre deux collections. Pour chaque élément de chaque collection, la valeur résultante sera positive si l'élément apparaît davantage de fois dans la collection \"expected\", négative s'il apparaît davantage de fois dans la collection \"actual\", et zéro s'il apparaît le même nombre de fois dans chaque collection.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'élément de la collection attendue. |
| T2 | Type d'élément de la collection réelle. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Collection attendue. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Collection réelle. |

### Valeur de retour

Carte des résultats de comparaison par valeur selon les règles ci-dessus.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Dictionary](../../../system.collections.generic/dictionary/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Structure [CollectionAssertHelper](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)