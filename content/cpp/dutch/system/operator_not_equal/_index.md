---
title: operator!=()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 2055
url: /nl/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) functie




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) functie




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) functie




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) functie


Bepaalt of het opgegeven [Nullable](../nullable/) object een waarde vertegenwoordigt die niet gelijk is aan null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | std::nullptr_t | Een constante referentie naar een [Nullable](../nullable/) object om te testen |

### Retourwaarde

Waar als het opgegeven object een niet-null waarde vertegenwoordigt, onwaar anders

## System::operator!=(const T1\&, const Nullable\<T2\>\&) functie


Bepaalt of de opgegeven waarde niet gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../nullable/) object door [operator!=()](./) toe te passen op deze waarden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de eerste vergelijkingswaarde |
| T2 | Het onderliggende type van het [Nullable](../nullable/) object dat de tweede vergelijkingswaarde vertegenwoordigt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | Een constante referentie naar de waarde die moet worden gebruikt als de eerste vergelijkingswaarde |
| other | const [Nullable](../nullable/)\<T2\>\& | Een constante referentie naar het [Nullable](../nullable/) object waarvan de vertegenwoordigde waarde moet worden gebruikt als de tweede vergelijkingswaarde |

### Retourwaarde

Waar als de te vergelijken waarden niet gelijk zijn, anders onwaar

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) functie


Vergelijkt twee slimme wijzen op ongelijkheid.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee-type van de eerste pointer. |
| Y | Pointee-type van de tweede pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Eerste pointer om te vergelijken. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Tweede pointer om te vergelijken. |

### Retourwaarde

Onwaar als de pointers gelijk zijn, waar anders.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) functie


Controleert of een slimme pointer niet null is.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee-type van de pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Pointer om te controleren. |

### Retourwaarde

Onwaar als de pointer null is, waar anders.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) functie


Controleert of een slimme pointer niet null is.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee-type van de pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | std::nullptr_t | Pointer om te controleren. |

### Retourwaarde

Onwaar als de pointer null is, waar anders.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) functie


Ongelijkheidsvergelijking van een slimme pointer met een eenvoudige (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | type van slimme pointer. |
| Y | type van eenvoudige pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | slimme pointer om te vergelijken (links). |
| y | const Y * | pointer om te vergelijken (rechts). |

### Retourwaarde

Onwaar als de pointers gelijk zijn, waar anders.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) functie


Gelijkheidsvergelijking van een eenvoudige (C) pointer met een slimme pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | type van eenvoudige pointer. |
| Y | type van slimme pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const X * | pointer om te vergelijken (rechts). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | slimme pointer om te vergelijken (links). |

### Retourwaarde

Onwaar als de pointers gelijk zijn, waar anders.

## System::operator!=(Chars\&, const String\&) functie


[String](../string/) vergelijking.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Chars | [String](../string/) literaaltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literaal om te vergelijken. |
| right | const [String](../string/)\& | [String](../string/) om te vergelijken. |

### Retourwaarde

onwaar als de strings gelijk zijn, waar anders.

## System::operator!=(T\&, const String\&) functie


[String](../string/) vergelijking.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [String](../string/) pointertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer om te vergelijken. |
| right | const [String](../string/)\& | [String](../string/) om te vergelijken. |

### Retourwaarde

onwaar als de strings gelijk zijn, waar anders.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) functie


[Object](../object/) en string-vergelijking.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) om te converteren naar string en te vergelijken. |
| right | const [String](../string/)\& | [String](../string/) om te vergelijken. |

### Retourwaarde

onwaar als de object-stringrepresentatie gelijk is aan de string, waar anders.

## System::operator!=(std::nullptr_t, const String\&) functie


Controleert of een string null is.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) om te controleren. |

### Retourwaarde

onwaar als de string null is, waar anders.

## System::operator!=(std::nullptr_t, TimeSpan) functie




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) functie


Bepaalt of de URI-s die door het huidige en het opgegeven object worden vertegenwoordigd, niet gelijk zijn.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Het eerste [Uri](../uri/) object om te vergelijken |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Het tweede [Uri](../uri/) object om te vergelijken |

### Retourwaarde

Waar als de URI-s niet gelijk zijn, anders onwaar

## Zie ook

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