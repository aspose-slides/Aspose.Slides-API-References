---
title: operator==()
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 2042
url: /de/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) Funktion




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) Funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) Funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) Funktion


Bestimmt, ob das angegebene [Nullable](../nullable/)-Objekt einen dem Nullwert entsprechenden Wert darstellt.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | std::nullptr_t | Eine konstante Referenz auf ein [Nullable](../nullable/)-Objekt zum Testen |

### Rückgabewert

True if the specified object represents null value, false otherwise

## System::operator==(const T1\&, const Nullable\<T2\>\&) Funktion


Bestimmt, ob der angegebene Wert dem von dem angegebenen [Nullable](../nullable/)-Objekt dargestellten Wert entspricht, indem [operator==()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des ersten zu vergleichenden Wertes |
| T2 | Der zugrunde liegende Typ des [Nullable](../nullable/)-Objekts, das den zweiten zu vergleichenden Wert darstellt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Eine konstante Referenz auf den Wert, der als erster zu vergleichender Operand verwendet werden soll |
| other | const [Nullable](../nullable/)\<T2\>\& | Eine konstante Referenz auf das [Nullable](../nullable/)-Objekt, dessen dargestellter Wert als zweiter zu vergleichender Operand verwendet werden soll |

### Rückgabewert

True if the comparands are equal, otherwise - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) Funktion


Vergleicht zwei Smart-Pointer auf Gleichheit.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp des ersten Zeigers. |
| Y | Zieltyp des zweiten Zeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Erster zu vergleichender Zeiger. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Zweiter zu vergleichender Zeiger. |

### Rückgabewert

True if pointers match, false otherwise.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) Funktion


Prüft, ob der Smart-Pointer Null ist.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp des Zeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | std::nullptr_t | Pointer to check. |

### Rückgabewert

True if pointer is null, false otherwise.

## System::operator==(const SmartPtr\<X\>\&, const Y *) Funktion


Gleichheitsvergleich eines Smart-Pointers mit einem einfachen (C-)Zeiger.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Typ des Smart-Pointers. |
| Y | Typ des einfachen Zeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Smart-Pointer zum Vergleich (links). |
| y | const Y * | Zeiger zum Vergleich (rechts). |

### Rückgabewert

True if pointers match, false otherwise.

## System::operator==(const X *, const SmartPtr\<Y\>\&) Funktion


Gleichheitsvergleich eines einfachen (C-)Zeigers mit einem Smart-Pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Typ des einfachen Zeigers. |
| Y | Typ des Smart-Pointers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const X * | Zeiger zum Vergleich (rechts). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Smart-Pointer zum Vergleich (links). |

### Rückgabewert

True if pointers match, false otherwise.

## System::operator==(T const\&, std::nullptr_t) Funktion


Prüft, ob ein Werttyp-Objekt (übersetzte C#-Struktur usw.) Null ist.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | T const\& | [Object](../object/) zum Prüfen. |

### Rückgabewert

True if object is null, false otherwise.

## System::operator==(std::nullptr_t, T const\&) Funktion


Prüft, ob ein Werttyp-Objekt (übersetzte C#-Struktur usw.) Null ist.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) zum Prüfen. |

### Rückgabewert

True if object is null, false otherwise.

## System::operator==(Chars\&, const String\&) Funktion


[String](../string/)-Vergleich.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Chars | [String](../string/) Literaltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | Chars\& | [String](../string/) Literale zum Vergleich. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleich. |

### Rückgabewert

true if strings match, false otherwise.

## System::operator==(T\&, const String\&) Funktion


[String](../string/)-Vergleich.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [String](../string/) Zeigertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | T\& | [String](../string/) Zeiger zum Vergleich. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleich. |

### Rückgabewert

true if strings match, false otherwise.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) Funktion


[Object](../object/)- und String-Vergleich.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) zum Umwandeln in einen String und zum Vergleich. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleich. |

### Rückgabewert

true if object string representation equals to string, false otherwise.

## System::operator==(std::nullptr_t, const String\&) Funktion


Prüft, ob der String Null ist.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) zum Prüfen. |

### Rückgabewert

true if string is null, false otherwise.

## System::operator==(std::nullptr_t, TimeSpan) Funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) Funktion


Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten URIs gleich sind.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Das erste [Uri](../uri/)-Objekt zum Vergleichen |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Das zweite [Uri](../uri/)-Objekt zum Vergleichen |

### Rückgabewert

True if URIs are equal, otherwise - false

## Siehe auch

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
* Struktur [IsNullable](../isnullable/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)