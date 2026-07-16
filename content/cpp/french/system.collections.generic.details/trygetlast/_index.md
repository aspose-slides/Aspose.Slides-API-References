---
title: TryGetLast()
second_title: Référence API Aspose.Slides pour C++
description: Tente d'obtenir le dernier élément de la collection.
type: docs
weight: 261
url: /fr/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) fonction

Tente d'obtenir le dernier élément de la collection.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la collection. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collection à partir de laquelle un élément doit être acquis. |
| found | **bool**\& | Le paramètre de sortie. Retourne true lorsque la collection contient un élément. Sinon false est retourné. |

### Valeur de retour

Retourne le dernier élément de la collection. La valeur par défaut du type sera retournée lorsque la collection est vide.

## Voir aussi

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)