---
title: operator==()
second_title: Aspose.Slides pro C++ – reference API
description: 
type: docs
weight: 2042
url: /cs/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) function




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) function


Určuje, zda daný objekt [Nullable](../nullable/) představuje hodnotu rovnající se null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### Návratová hodnota

True, pokud daný objekt představuje hodnotu null, false jinak

## System::operator==(const T1\&, const Nullable\<T2\>\&) function


Určuje, zda je zadaná hodnota rovna hodnotě reprezentované zadaným objektem [Nullable](../nullable/) použitím [operator==()](./) na těchto hodnotách.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ první porovnávané hodnoty |
| T2 | Základní typ objektu [Nullable](../nullable/), který představuje druhou porovnávanou hodnotu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| some | const T1\& | Konstantní reference na hodnotu, která má být použita jako první operand |
| other | const [Nullable](../nullable/)\<T2\>\& | Konstantní reference na objekt [Nullable](../nullable/), jehož reprezentovaná hodnota má být použita jako druhý operand |

### Návratová hodnota

True, pokud jsou operandy rovny, jinak - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function


Porovnává rovnost dvou chytrých ukazatelů.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ objektu, na který ukazuje první ukazatel. |
| Y | Typ objektu, na který ukazuje druhý ukazatel. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | První ukazatel k porovnání. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Druhý ukazatel k porovnání. |

### Návratová hodnota

True, pokud se ukazatele shodují, false jinak.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) function


Kontroluje, zda je chytrý ukazatel null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ objektu, na který ukazuje ukazatel. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | std::nullptr_t | Ukazatel k prověření. |

### Návratová hodnota

True, pokud je ukazatel null, false jinak.

## System::operator==(const SmartPtr\<X\>\&, const Y *) function


Porovnání rovnosti chytrého ukazatele s jednoduchým (C) ukazatelem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
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

True, pokud se ukazatele shodují, false jinak.

## System::operator==(const X *, const SmartPtr\<Y\>\&) function


Porovnání rovnosti jednoduchého (C) ukazatele s chytrým ukazatelem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
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

True, pokud se ukazatele shodují, false jinak.

## System::operator==(T const\&, std::nullptr_t) function


Kontroluje, zda je objekt typu hodnoty (přeložená struktura C# atd.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | T const\& | [Object](../object/) k prověření. |

### Návratová hodnota

True, pokud je objekt null, false jinak.

## System::operator==(std::nullptr_t, T const\&) function


Kontroluje, zda je objekt typu hodnoty (přeložená struktura C# atd.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) k prověření. |

### Návratová hodnota

True, pokud je objekt null, false jinak.

## System::operator==(Chars\&, const String\&) function


[String](../string/) porovnání.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
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

true, pokud se řetězce shodují, false jinak.

## System::operator==(T\&, const String\&) function


[String](../string/) porovnání.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
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

true, pokud se řetězce shodují, false jinak.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) function


[Object](../object/) a porovnání řetězce.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) pro konverzi na řetězec a porovnání. |
| right | const [String](../string/)\& | [String](../string/) k porovnání. |

### Návratová hodnota

true, pokud se řetězce shodují, false jinak.

## System::operator==(std::nullptr_t, const String\&) function


Kontroluje, zda je řetězec null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) k prověření. |

### Návratová hodnota

true, pokud je řetězec null, false jinak.

## System::operator==(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function


Určuje, zda jsou URI reprezentované aktuálním a zadaným objektem stejné.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | První objekt [Uri](../uri/) k porovnání |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Druhý objekt [Uri](../uri/) k porovnání |

### Návratová hodnota

True, pokud jsou URI rovny, jinak - false

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