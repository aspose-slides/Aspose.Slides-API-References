---
title: operator[]()
second_title: Référence API Aspose.Slides pour C++
description: Opérateur d’accès pour travailler avec la conversion du type de clé.
type: docs
weight: 14
url: /fr/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const méthode

Access operator to work with key type conversion.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type de clé source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) clé. |

### Valeur de retour

Référence à la valeur correspondant à la clé fournie, existante ou nouvellement créée.

## DictionaryPtr::operator[](const T\&) const méthode

Access operator.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) clé. |

### Valeur de retour

Référence à la valeur correspondant à la clé fournie, existante ou nouvellement créée.

## Voir aussi

* Classe [DictionaryPtr](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)