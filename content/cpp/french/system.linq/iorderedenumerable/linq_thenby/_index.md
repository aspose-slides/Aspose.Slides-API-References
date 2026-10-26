---
title: LINQ_ThenBy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue un tri supplémentaire des éléments d'une séquence en ordre croissant selon une clé.
type: docs
weight: 27
url: /fr/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) méthode

Effectue un tri supplémentaire des éléments d'une séquence en ordre croissant selon une clé.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Key | Le type de la clé renvoyé par keySelector. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Une fonction permettant d'extraire une clé de chaque élément. |

### Valeur de retour

[System::Linq::IOrderedEnumerable](../) dont les éléments sont triés selon une clé.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) méthode




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)