---
title: MakeYieldEnumerable()
second_title: Référence API Aspose.Slides pour C++
description: Crée un IEnumerable à partir d'une fonction yield.
type: docs
weight: 2380
url: /fr/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

Crée un IEnumerable à partir d'une fonction yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la séquence |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La fonction yield à exécuter |

### Valeur de retour

Pointeur partagé vers l'IEnumerable

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)