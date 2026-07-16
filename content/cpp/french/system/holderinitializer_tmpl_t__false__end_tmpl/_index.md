---
title: HolderInitializer< T, false >
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécialisation de HolderInitializer pour le cas où T est un type valeur. Le contexte d'utilisation permet de retourner une référence à des objets temporaires, car il est garanti que l'instance sera copiée par l'appelant. Ainsi, cette spécialisation est utilisée uniquement comme un stub et ne fait rien.
type: docs
weight: 1626
url: /fr/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) spécialisation pour le cas où T est un type valeur. Le contexte d'utilisation permet de retourner une référence à des objets temporaires, car il est garanti que l'instance sera copiée par l'appelant. Ainsi, cette spécialisation est utilisée uniquement comme un stub, et ne fait rien.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Méthodes

| Méthode | Description |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)