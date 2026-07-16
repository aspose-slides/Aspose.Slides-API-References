---
title: LastIndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche l'objet spécifié et renvoie l'index zéro-basé de la dernière occurrence dans la liste entière.
type: docs
weight: 469
url: /fr/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const method

Recherche l'objet spécifié et renvoie l'index zéro-basé de la dernière occurrence dans la liste entière.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | L'objet à localiser dans la liste |

### Valeur de retour

L'index zéro-basé de la dernière occurrence de l'item dans le [List](../) complet, s'il est trouvé ; sinon, -1.

## List::LastIndexOf(const T\&, int32_t) const method

Recherche l'objet spécifié et renvoie l'index zéro-basé de la dernière occurrence dans la plage d'éléments du [List](../) qui s'étend du premier élément à l'index spécifié.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | L'objet à localiser dans la liste |
| index | **int32_t** | L'index de départ zéro-basé de la recherche en arrière. |

### Valeur de retour

L'index zéro-basé de la dernière occurrence de l'item dans la plage d'éléments du [List](../) qui s'étend du premier élément à l'index, s'il est trouvé ; sinon, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const method

Recherche l'objet spécifié et renvoie l'index zéro-basé de la dernière occurrence dans la plage d'éléments du [List](../) qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| item | const T\& | L'objet à localiser dans le [List](../) |
| index | **int32_t** | L'index de départ zéro-basé de la recherche en arrière. |
| count | **int32_t** | Le nombre d'éléments dans la section à rechercher. |

### Valeur de retour

L'index zéro-basé de la dernière occurrence de l'item dans la plage d'éléments du [List](../) qui contient le nombre count d'éléments et se termine à l'index, s'il est trouvé ; sinon, -1.

## Voir aussi

* Classe [List](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)