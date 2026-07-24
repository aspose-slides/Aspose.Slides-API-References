---
title: operator!=()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 2055
url: /de/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) Funktion




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) Funktion




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) Funktion




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) Funktion


Bestimmt, ob das angegebene [Nullable](../nullable/)-Objekt einen Wert darstellt, der nicht gleich null ist.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | std::nullptr_t | Eine konstante Referenz auf ein [Nullable](../nullable/)-Objekt zum Testen |

### Rückgabewert

true, wenn das angegebene Objekt einen Nicht-null-Wert darstellt, sonst false

## System::operator!=(const T1\&, const Nullable\<T2\>\&) Funktion


Bestimmt, ob der angegebene Wert nicht gleich dem von dem angegebenen [Nullable](../nullable/)-Objekt dargestellten Wert ist, indem [operator!=()](./) auf diese Werte angewendet wird.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des ersten zu vergleichenden Werts |
| T2 | Der zugrunde liegende Typ des [Nullable](../nullable/)-Objekts, das den zweiten zu vergleichenden Wert darstellt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Eine konstante Referenz auf den Wert, der als erster Vergleichswert verwendet werden soll |
| other | const [Nullable](../nullable/)\<T2\>\& | Eine konstante Referenz auf das [Nullable](../nullable/)-Objekt, dessen dargestellter Wert als zweiter Vergleichswert verwendet werden soll |

### Rückgabewert

true, wenn die Vergleichswerte nicht gleich sind, sonst false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) Funktion


Vergleicht zwei Smart-Pointer auf Ungleichheit.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Vorlagenparameter

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

false, wenn die Zeiger übereinstimmen, sonst true

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) Funktion


Prüft, ob der Smart-Pointer nicht null ist.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp des Zeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Zu prüfender Zeiger. |

### Rückgabewert

false, wenn der Zeiger null ist, sonst true

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) Funktion


Prüft, ob der Smart-Pointer nicht null ist.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp des Zeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | std::nullptr_t | Zu prüfender Zeiger. |

### Rückgabewert

false, wenn der Zeiger null ist, sonst true

## System::operator!=(const SmartPtr\<X\>\&, const Y *) Funktion


Ungleichheitsvergleich eines Smart-Pointers mit einem einfachen (C)-Zeiger.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Vorlagenparameter

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

false, wenn die Zeiger übereinstimmen, sonst true

## System::operator!=(const X *, const SmartPtr\<Y\>\&) Funktion


Gleichheitsvergleich eines Smart-Pointers mit einem einfachen (C)-Zeiger.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Vorlagenparameter

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

false, wenn die Zeiger übereinstimmen, sonst true

## System::operator!=(Chars\&, const String\&) Funktion


[String](../string/) Vergleich.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Chars | [String](../string/) Literaltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | Chars\& | [String](../string/) Literal zum Vergleichen. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleichen. |

### Rückgabewert

false, wenn die Zeichenketten übereinstimmen, sonst true

## System::operator!=(T\&, const String\&) Funktion


[String](../string/) Vergleich.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | [String](../string/) Zeigertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | T\& | [String](../string/) Zeiger zum Vergleichen. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleichen. |

### Rückgabewert

false, wenn die Zeichenketten übereinstimmen, sonst true

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) Funktion


[Object](../object/) und Zeichenkettenvergleich.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) zum Konvertieren in eine Zeichenkette und zum Vergleichen. |
| right | const [String](../string/)\& | [String](../string/) zum Vergleichen. |

### Rückgabewert

false, wenn die Objekt-Zeichenkettenrepräsentation der Zeichenkette entspricht, sonst true

## System::operator!=(std::nullptr_t, const String\&) Funktion


Prüft, ob die Zeichenkette null ist.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) zum Prüfen. |

### Rückgabewert

false, wenn die Zeichenkette null ist, sonst true

## System::operator!=(std::nullptr_t, TimeSpan) Funktion




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) Funktion


Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten URIs nicht gleich sind.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Das erste [Uri](../uri/)-Objekt zum Vergleich |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Das zweite [Uri](../uri/)-Objekt zum Vergleich |

### Rückgabewert

true, wenn die URIs nicht gleich sind, sonst false

## Siehe auch

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