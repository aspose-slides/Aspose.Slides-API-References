---
title: operator+()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une instance de la classe Nullable<T> construite par défaut.
type: docs
weight: 209
url: /fr/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const méthode

Renvoie une instance construite par défaut de la classe Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const méthode

Additionne les valeurs nullable et non nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const T1\& | valeur à ajouter. |

### Valeur de retour

Résultat de l'addition.

## Nullable::operator+(const Nullable\<T1\>\&) const méthode

Additionne les valeurs nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valeur à ajouter. |

### Valeur de retour

Résultat de l'addition.

## Voir aussi

* Classe [Nullable](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)