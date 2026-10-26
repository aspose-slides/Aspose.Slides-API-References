---
title: operator-()
second_title: Référence API Aspose.Slides pour C++
description: Soustrait des valeurs nullables et null-pointées.
type: docs
weight: 222
url: /fr/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const méthode

Soustrait des valeurs nullables et null-pointées.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de l'opérande droit, doit être nullptr_t. |

### Valeur de retour

Objet [Nullable](../) vide.

## Nullable::operator-(const T1&) const méthode

Soustrait des valeurs nullables et non nullables.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de l'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | valeur à soustraire. |

### Valeur de retour

Résultat de la soustraction.

## Nullable::operator-(const Nullable\<T1\>\&) const méthode

Soustrait des valeurs nullables.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de l'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valeur à soustraire. |

### Valeur de retour

Résultat de la soustraction.

## Voir aussi

* Classe [Nullable](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)