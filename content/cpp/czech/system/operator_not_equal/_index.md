---
title: operator!=()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 2055
url: /cs/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) funkce

```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```
## System::operator!=(std::nullptr_t, DateTime) funkce

```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) funkce

```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) funkce

Určuje, zda zadaný [Nullable](../nullable/) objekt představuje hodnotu, která není rovna null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | std::nullptr_t | Konstantní reference na objekt [Nullable](../nullable/) k testování |

### Návratová hodnota

True pokud zadaný objekt představuje nenulovou hodnotu, false jinak

## System::operator!=(const T1\&, const Nullable\<T2\>\&) funkce

Určuje, zda zadaná hodnota není rovna hodnotě představované zadaným [Nullable](../nullable/) objektem použitím [operator!=()](./) na tyto hodnoty.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ první porovnávané hodnoty |
| T2 | Základní typ [Nullable](../nullable/) objektu, který představuje druhou porovnávanou hodnotu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| some | const T1\& | Konstantní reference na hodnotu, která má být použita jako první srovnávaná hodnota |
| other | const [Nullable](../nullable/)\<T2\>\& | Konstantní reference na objekt [Nullable](../nullable/), jehož představovaná hodnota má být použita jako druhá srovnávaná hodnota |

### Návratová hodnota

True pokud srovnávané hodnoty nejsou rovny, jinak - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) funkce

Porovnává nerovnost dvou chytrých ukazatelů.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ ukazovaného objektu prvního ukazatele. |
| Y | Typ ukazovaného objektu druhého ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | První ukazatel k porovnání. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Druhý ukazatel k porovnání. |

### Návratová hodnota

False pokud se ukazatele shodují, true jinak.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) funkce

Kontroluje, zda chytrý ukazatel není null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ ukazovaného objektu ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Ukazatel ke kontrole. |

### Návratová hodnota

False pokud je ukazatel null, true jinak.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) funkce

Kontroluje, zda chytrý ukazatel není null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ ukazovaného objektu ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | std::nullptr_t | Ukazatel ke kontrole. |

### Návratová hodnota

False pokud je ukazatel null, true jinak.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) funkce

Porovnání nerovnosti chytrého ukazatele se jednoduchým (C) ukazatelem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | typ chytrého ukazatele. |
| Y | typ jednoduchého ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | chytrý ukazatel k porovnání (levý). |
| y | const Y * | ukazatel k porovnání (pravý). |

### Návratová hodnota

False pokud se ukazatele shodují, true jinak.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) funkce

Porovnání rovnosti chytrého ukazatele se jednoduchým (C) ukazatelem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | typ jednoduchého ukazatele. |
| Y | typ chytrého ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const X * | ukazatel k porovnání (pravý). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | chytrý ukazatel k porovnání (levý). |

### Návratová hodnota

False pokud se ukazatele shodují, true jinak.

## System::operator!=(Chars\&, const String\&) funkce

[String](../string/) porovnání.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Chars | [String](../string/) typ literálu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literál k porovnání. |
| right | const [String](../string/)\& | [String](../string/) k porovnání. |

### Návratová hodnota

false pokud se řetězce shodují, true jinak.

## System::operator!=(T\&, const String\&) funkce

[String](../string/) porovnání.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [String](../string/) typ ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | T\& | [String](../string/) ukazatel k porovnání. |
| right | const [String](../string/)\& | [String](../string/) k porovnání. |

### Návratová hodnota

false pokud se řetězce shodují, true jinak.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) funkce

[Object](../object/) a porovnání řetězce.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) pro převod na řetězec a porovnání. |
| right | const [String](../string/)\& | [String](../string/) k porovnání. |

### Návratová hodnota

false pokud se řetězcová reprezentace objektu rovná řetězci, true jinak.

## System::operator!=(std::nullptr_t, const String\&) funkce

Kontroluje, zda je řetězec null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) ke kontrole. |

### Návratová hodnota

false pokud je řetězec null, true jinak.

## System::operator!=(std::nullptr_t, TimeSpan) funkce

```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) funkce

Určuje, zda URI reprezentované aktuálním a zadaným objektem nejsou rovny.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | První objekt [Uri](../uri/) k porovnání |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Druhý objekt [Uri](../uri/) k porovnání |

### Návratová hodnota

True pokud URI nejsou rovny, jinak - false

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)