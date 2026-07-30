---
title: Equals()
second_title: Aspose.Slides pro C++ referenční příručka API
description: 
type: docs
weight: 14
url: /cs/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metoda




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metoda


Náhrada pro volání C# [Object.Equals](../../object/equals/) fungující pro libovolný typ v C++. Přetížení pro typy chytrých ukazatelů.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Návratová hodnota

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(T, const T2\&) metoda


Náhrada pro volání C# [Object.Equals](../../object/equals/) fungující pro libovolný typ v C++. Přetížení pro typy struktur.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Návratová hodnota

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const T\&, const T2\&) metoda


Náhrada pro volání C# [Object.Equals](../../object/equals/) fungující pro libovolný typ v C++. Přetížení pro skalární typy.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Návratová hodnota

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const char_t(&), String) metoda


Náhrada pro volání C# [Object.Equals](../../object/equals/) fungující pro libovolný typ v C++. Přetížení pro řetězcový literál s porovnáním řetězců.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| N | [String](../../string/) literal size. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Návratová hodnota

True if strings match, false otherwise.

## ObjectExt::Equals(const float\&, const float\&) metoda


Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point value. |
| another | const **float**\& | RHS floating point value. |

### Návratová hodnota

True if **obj** and **another** are both NaN or equal, false otherwise.

## ObjectExt::Equals(const double\&, const double\&) metoda


Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point value. |
| another | const **double**\& | RHS floating point value. |

### Návratová hodnota

True if **obj** and **another** are both NaN or equal, false otherwise.

## Viz také

* Třída [ObjectExt](../)
* Třída [String](../../string/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)