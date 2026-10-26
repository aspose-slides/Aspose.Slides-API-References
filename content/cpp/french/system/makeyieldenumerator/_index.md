---
title: MakeYieldEnumerator()
second_title: Référence API Aspose.Slides pour C++
description: Crée un IEnumerator à partir d'une fonction yield.
type: docs
weight: 2393
url: /fr/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) fonction

Creates an IEnumerator from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of elements in the sequence |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### Valeur de retour

Shared pointer to the IEnumerator

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerator](../../system.collections.generic/ienumerator/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)