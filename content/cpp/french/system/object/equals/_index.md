---
title: Equals()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les objets en utilisant la sémantique C# Object.Equals.
type: docs
weight: 157
url: /fr/system/object/equals/
---
## Object::Equals(ptr) méthode

Compare les objets en utilisant la sémantique C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) à comparer à l'actuel. |

### Valeur de retour

Vrai si les objets sont considérés égaux et faux sinon.

## Object::Equals(T1 const\&, T2 const\&) méthode

Compare les objets de type référence dans le style C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type du premier objet à comparer. |
| T2 | Type du deuxième objet à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | T1 const\& | Premier objet à comparer. |
| objB | T2 const\& | Deuxième objet à comparer. |

### Valeur de retour

Vrai si les objets correspondent soit par référence, soit sémantiquement (par comparaison de type [Object.Equals](./)), faux sinon.

## Object::Equals(T1 const\&, T2 const\&) méthode

Compare les objets de type valeur dans le style C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type du premier objet à comparer. |
| T2 | Type du deuxième objet à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | T1 const\& | Premier objet à comparer. |
| objB | T2 const\& | Deuxième objet à comparer. |

### Valeur de retour

Vrai si les objets sont considérés égaux grâce à l'opérateur d'égalité disponible, faux sinon.

## Object::Equals(float const\&, float const\&) méthode

Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | **float** const\& | Valeur à virgule flottante du côté gauche. |
| objB | **float** const\& | Valeur à virgule flottante du côté droit. |

### Valeur de retour

Vrai si **objA** et **objB** sont tous deux NaN ou égaux, faux sinon.

## Object::Equals(double const\&, double const\&) méthode

Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| objA | **double** const\& | Valeur à virgule flottante double du côté gauche. |
| objB | **double** const\& | Valeur à virgule flottante double du côté droit. |

### Valeur de retour

Vrai si **objA** et **objB** sont tous deux NaN ou égaux, faux sinon.

## Voir aussi

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)