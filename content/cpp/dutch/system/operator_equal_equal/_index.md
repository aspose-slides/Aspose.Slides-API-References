---
title: operator==()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 2042
url: /nl/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) functie




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) functie




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) functie




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) functie


Bepaalt of het opgegeven [Nullable](../nullable/) object een waarde vertegenwoordigt die gelijk is aan null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### Retourwaarde

True if the specified object represents null value, false otherwise

## System::operator==(const T1\&, const Nullable\<T2\>\&) functie


Bepaalt of de opgegeven waarde gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../nullable/) object door [operator==()](./) op deze waarden toe te passen.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Retourwaarde

True if the comparands are equal, otherwise - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) functie


Vergelijkt twee slimme pointers op gelijkheid.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee type of first pointer. |
| Y | Pointee type of second pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | First pointer to compare. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Second pointer to compare. |

### Retourwaarde

True if pointers match, false otherwise.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) functie


Controleert of de slimme pointer null is.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee type of pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | std::nullptr_t | Pointer to check. |

### Retourwaarde

True if pointer is null, false otherwise.

## System::operator==(const SmartPtr\<X\>\&, const Y *) functie


Gelijkheidsvergelijking van een slimme pointer met een eenvoudige (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | type of smart pointer. |
| Y | type of simple pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer to compare (left). |
| y | const Y * | pointer to compare (right). |

### Retourwaarde

True if pointers match, false otherwise.

## System::operator==(const X *, const SmartPtr\<Y\>\&) functie


Gelijkheidsvergelijking van een slimme pointer met een eenvoudige (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | type of simple pointer. |
| Y | type of smart pointer. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const X * | pointer to compare (right). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer to compare (left). |

### Retourwaarde

True if pointers match, false otherwise.

## System::operator==(T const\&, std::nullptr_t) functie


Controleert of een waarde-typering object (vertaling van C#-structuur, etc.) null is.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Value type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | T const\& | [Object](../object/) to check. |

### Retourwaarde

True if object is null, false otherwise.

## System::operator==(std::nullptr_t, T const\&) functie


Controleert of een waarde-typering object (vertaling van C#-structuur, etc.) null is.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Value type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) to check. |

### Retourwaarde

True if object is null, false otherwise.

## System::operator==(Chars\&, const String\&) functie


[String](../string/) vergelijking.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Chars | [String](../string/) lettertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | Chars\& | [String](../string/) lettertype om te vergelijken. |
| right | const [String](../string/)\& | [String](../string/) om te vergelijken. |

### Retourwaarde

true als strings overeenkomen, false anders

## System::operator==(T\&, const String\&) functie


[String](../string/) vergelijking.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
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

true als strings overeenkomen, false anders

## System::operator==(const SharedPtr\<Object\>\&, const String\&) functie


[Object](../object/) en stringvergelijking.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) om te converteren naar string en te vergelijken. |
| right | const [String](../string/)\& | [String](../string/) om te vergelijken. |

### Retourwaarde

true als object string representation equals to string, false otherwise.

## System::operator==(std::nullptr_t, const String\&) functie


Controleert of de string null is.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) om te controleren. |

### Retourwaarde

true als string null is, false anders.

## System::operator==(std::nullptr_t, TimeSpan) functie




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) functie


Bepaalt of de door het huidige en opgegeven objecten gerepresenteerde URI's gelijk zijn.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Het eerste [Uri](../uri/) object om te vergelijken |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Het tweede [Uri](../uri/) object om te vergelijken |

### Retourwaarde

True als URI's gelijk zijn, anders - false

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [ArraySegment](../arraysegment/)
* Klasse [DateTime](../datetime/)
* Klasse [DateTimeOffset](../datetimeoffset/)
* Klasse [Nullable](../nullable/)
* Klasse [SmartPtr](../smartptr/)
* Klasse [Object](../object/)
* Klasse [String](../string/)
* Klasse [TimeSpan](../timespan/)
* Klasse [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Naamruimte [System](../)
* Library [Aspose.Slides](../../)