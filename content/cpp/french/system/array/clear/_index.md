---
title: Clear()
second_title: Référence API Aspose.Slides pour C++
description: Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule.
type: docs
weight: 53
url: /fr/system/array/clear/
---
## Array::Clear() méthode


Non pris en charge car le tableau représenté par l’objet actuel est en lecture seule.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) méthode


Remplace **count** valeurs à partir de l’index **startIndex** dans le tableau spécifié par les valeurs par défaut.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Type | Type of elements in the target array |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Tableau cible |
| startIndex | int | Index à partir duquel commencer le remplacement des éléments |
| count | int | Nombre d'éléments à remplacer |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Méthode [Type](../../object/type/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)