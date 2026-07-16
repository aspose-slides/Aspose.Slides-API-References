---
title: IsNull()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si la valeur spécifiée est nulle. Version pour les types arithmétiques et d'énumération.
type: docs
weight: 1
url: /fr/system/testtools/isnull/
---
## TestTools::IsNull(T) méthode


Vérifie si la valeur spécifiée est nulle. [Version](../../version/) pour les types arithmétiques et d'énumération.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur à vérifier. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T | Valeur à vérifier pour null. |

### Valeur de retour

Toujours retourne faux.

## TestTools::IsNull(const T\&) méthode


Vérifie si la valeur spécifiée est nulle. [Version](../../version/) pour les types de valeur non arithmétiques et non d'énumération.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur à vérifier. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | Valeur à vérifier pour null. |

### Valeur de retour

Vrai si l'objet est comparé à nullptr comme vrai, faux sinon.

## TestTools::IsNull(const SharedPtr\<T\>\&) méthode


Vérifie si la valeur spécifiée est nulle. [Version](../../version/) pour les types de valeur non arithmétiques.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur à vérifier. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Valeur à vérifier pour null. |

### Valeur de retour

Vrai si l'objet est comparé à nullptr comme vrai, faux sinon.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) méthode


Vérifie si la valeur spécifiée est nulle. [Version](../../version/) pour les paires clé-valeur.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| K | Type de clé. |
| V | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Objet paire. |

### Valeur de retour

Vrai si la paire est considérée comme nulle, faux sinon.

## TestTools::IsNull(const System::String\&) méthode


Vérifie si la chaîne est nulle.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) à vérifier. |

### Valeur de retour

Vrai si la chaîne est considérée comme nulle, faux sinon.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)