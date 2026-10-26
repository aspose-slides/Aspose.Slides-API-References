---
title: Equals()
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 14
url: /fr/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) méthode




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) méthode


Substitution des appels C# [Object.Equals](../../object/equals/) fonctionnant pour tout type en C++. Surcharge pour les types pointeur intelligent.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Valeur de retour

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(T, const T2\&) méthode


Substitution des appels C# [Object.Equals](../../object/equals/) fonctionnant pour tout type en C++. Surcharge pour les types de structures.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Valeur de retour

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const T\&, const T2\&) méthode


Substitution des appels C# [Object.Equals](../../object/equals/) fonctionnant pour tout type en C++. Surcharge pour les types scalaires.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Valeur de retour

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const char_t(&), String) méthode


Substitution des appels C# [Object.Equals](../../object/equals/) fonctionnant pour tout type en C++. Surcharge pour les littéraux de chaîne avec comparaison de chaînes.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| N | [String](../../string/) literal size. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Valeur de retour

True if strings match, false otherwise.

## ObjectExt::Equals(const float\&, const float\&) méthode


Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point value. |
| another | const **float**\& | RHS floating point value. |

### Valeur de retour

True if **obj** and **another** are both NaN or equal, false otherwise.

## ObjectExt::Equals(const double\&, const double\&) méthode


Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point value. |
| another | const **double**\& | RHS floating point value. |

### Valeur de retour

True if **obj** and **another** are both NaN or equal, false otherwise.

## Voir aussi

* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Structure [IsExceptionWrapper](../../isexceptionwrapper/)
* Structure [IsSmartPtr](../../issmartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)