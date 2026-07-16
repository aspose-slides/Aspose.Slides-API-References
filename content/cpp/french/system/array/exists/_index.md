---
title: Exists()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si l'objet Array spécifié contient un élément qui satisfait les exigences du prédicat spécifié.
type: docs
weight: 781
url: /fr/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) méthode

Détermine si l'objet [Array](../) spécifié contient un élément qui satisfait les exigences du prédicat spécifié.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Le tableau dans lequel rechercher l'élément |
| match | std::function\<**bool**(T)> | Objet fonction qui définit les exigences et vérifie si un élément les satisfait |

### Valeur de retour

Vrai si **arr** contient un élément qui satisfait les exigences définies par **match**

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)