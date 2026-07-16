---
title: operator=()
second_title: Référence API Aspose.Slides pour C++
description: Attribue null à l'objet actuel.
type: docs
weight: 14
url: /fr/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) méthode

Attribue null à l'objet actuel.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Valeur de retour

Un objet [Nullable](../) qui représente une valeur null.

## Nullable::operator=(const T1\&) méthode

Remplace la valeur actuellement représentée par l'objet par la valeur spécifiée.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Le | type de la nouvelle valeur à représenter par l'objet actuel |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const T1\& | La nouvelle valeur à représenter par l'objet actuel |

### Valeur de retour

Une référence à l'objet lui-même

## Nullable::operator=(const Nullable\<T1\>\&) méthode

Remplace la valeur actuellement représentée par l'objet par la valeur spécifiée.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Le | type de la nouvelle valeur à représenter par l'objet actuel |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | La nouvelle valeur à représenter par l'objet actuel |

### Valeur de retour

Une référence à l'objet lui-même

## Voir aussi

* Classe [Nullable](../)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)