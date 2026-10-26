---
title: CollectionAssertHelper
second_title: Référence de l'API Aspose.Slides pour C++
description: API Heler pour les opérations liées aux collections.
type: docs
weight: 1522
url: /fr/system/collectionasserthelper/
---
## CollectionAssertHelper struct

API Heler pour les opérations liées aux collections.

```cpp
class CollectionAssertHelper
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Vérifie que tous les éléments de la collection respectent le prédicat. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Vérifie que n'importe quel élément de la collection respecte le prédicat. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Sérialise deux collections pour la représentation du message. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Convertit la collection en chaîne en concaténant les représentations sous forme de chaîne des éléments. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Calcule la ‘diff’ entre deux collections. Pour chaque élément de chaque collection en tant que clé, la valeur résultante sera positive si l'élément apparaît plus souvent dans la collection \"expected\", négative s'il apparaît plus souvent dans la collection \"actual\" et zéro s'il apparaît le même nombre de fois dans chaque collection. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formate la chaîne à utiliser comme texte du message. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)