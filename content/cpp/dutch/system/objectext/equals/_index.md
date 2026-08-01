---
title: Equals()
second_title: Aspose.Slides voor C++ API Referentie
description: 
type: docs
weight: 14
url: /nl/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) methode




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) methode


Vervanging voor C# [Object.Equals](../../object/equals/) oproepen die werken voor elk type in C++. Overload voor smart pointer-typen.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Retourwaarde

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(T, const T2\&) methode


Vervanging voor C# [Object.Equals](../../object/equals/) oproepen die werken voor elk type in C++. Overload voor struct-typen.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Retourwaarde

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const T\&, const T2\&) methode


Vervanging voor C# [Object.Equals](../../object/equals/) oproepen die werken voor elk type in C++. Overload voor scalair-typen.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Retourwaarde

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const char_t(&), String) methode


Vervanging voor C# [Object.Equals](../../object/equals/) oproepen die werken voor elk type in C++. Overload voor stringliteral met stringvergelijking.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| N | [String](../../string/) literalgrootte. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Retourwaarde

True if strings match, false otherwise.

## ObjectExt::Equals(const float\&, const float\&) methode


Emuleert C#-stijl floating point-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al beschrijft IEC 60559:1989 dat NaN niet gelijk is aan enige waarde, inclusief NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point-waarde. |
| another | const **float**\& | RHS floating point-waarde. |

### Retourwaarde

True if **obj** and **another** are both NaN or equal, false otherwise.

## ObjectExt::Equals(const double\&, const double\&) methode


Emuleert C#-stijl floating point-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al beschrijft IEC 60559:1989 dat NaN niet gelijk is aan enige waarde, inclusief NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point-waarde. |
| another | const **double**\& | RHS floating point-waarde. |

### Retourwaarde

True if **obj** and **another** are both NaN or equal, false otherwise.

## Zie ook

* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)