---
title: ReferenceEquals()
second_title: Référence API Aspose.Slides pour C++
description: "Spécialisation de Object::ReferenceEquals pour le cas d'une chaîne et nullptr."
type: docs
weight: 261
url: /fr/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) méthode


Spécialisation de [Object::ReferenceEquals](./) pour le cas d'une chaîne et nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) à comparer à nullptr. |

### Valeur de retour

true si la chaîne est null, false sinon.

## Object::ReferenceEquals(String const\&, String const\&) méthode


Spécialisation de [Object::ReferenceEquals](./) pour le cas de chaînes.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Première chaîne à comparer. |
| str2 | [String](../../string/) const\& | Deuxième chaîne à comparer. |

### Valeur de retour

true si les chaînes correspondent, false sinon.

## Object::ReferenceEquals(ptr const\&, ptr const\&) méthode


Compare les objets par référence.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Premier pointeur à comparer. |
| objB | [ptr](../ptr/) const\& | Second pointeur à comparer. |

### Valeur de retour

True si les pointeurs correspondent et false sinon.

## Object::ReferenceEquals(T const\&, T const\&) méthode


Compare les objets par référence.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type des objets à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | T const\& | Premier objet à comparer. |
| objB | T const\& | Second objet à comparer. |

### Valeur de retour

True si les adresses des objets correspondent et false sinon.

## Object::ReferenceEquals(T const\&, std::nullptr_t) méthode


Compare par référence un objet de type valeur avec nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | T const\& | Premier objet à comparer. |

### Valeur de retour

Always returns false as value types cannot be nulled.

## Voir aussi

* Typedef [ptr](../ptr/)
* Classe [String](../../string/)
* Classe [Object](../)
* Structure [IsSmartPtr](../../issmartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)