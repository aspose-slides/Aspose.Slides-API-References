---
title: TryGetFirst()
second_title: Référence de l'API Aspose.Slides pour C++
description: Tente d'obtenir le premier élément de la collection.
type: docs
weight: 248
url: /fr/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) fonction


Tente d'obtenir le premier élément de la collection.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la collection. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collection dont un élément doit être acquis. |
| found | **bool**\& | Le paramètre de sortie. Renvoie true lorsque la collection contient un élément. Sinon, false est renvoyé. |

### Valeur de retour

Renvoie le premier élément de la collection. La valeur par défaut du type sera renvoyée lorsque la collection est vide.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) fonction


Tente d'obtenir le premier élément de la collection qui satisfait la fonction prédicat.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la collection. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collection dont un élément doit être acquis. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | La fonction prédicat. |
| found | **bool**\& | Le paramètre de sortie. Renvoie true lorsque la collection contient un élément. Sinon, false est renvoyé. |

### Valeur de retour

Renvoie le premier élément de la collection. La valeur par défaut du type sera renvoyée lorsqu'aucun élément ne satisfait la fonction prédicat spécifiée.

## Voir aussi

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Classe [Func](../../system/func/)
* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)