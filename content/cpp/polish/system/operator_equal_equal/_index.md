---
title: operator==()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: 
type: docs
weight: 2042
url: /pl/system/operator_equal_equal/
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


Określa, czy podany obiekt [Nullable](../nullable/) reprezentuje wartość równą null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | std::nullptr_t | Stałe odwołanie do obiektu [Nullable](../nullable/) do testu |

### Wartość zwracana

True, jeśli określony obiekt reprezentuje wartość null, w przeciwnym razie false

## System::operator==(const T1\&, const Nullable\<T2\>\&) function


Określa, czy podana wartość jest równa wartości reprezentowanej przez określony obiekt [Nullable](../nullable/) poprzez zastosowanie [operator==()](./) do tych wartości.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ pierwszej wartości porównywanej |
| T2 | Podstawowy typ obiektu [Nullable](../nullable/) reprezentującego drugą wartość porównywaną |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| some | const T1\& | Stałe odwołanie do wartości, która ma być użyta jako pierwsza porównywana wartość |
| other | const [Nullable](../nullable/)\<T2\>\& | Stałe odwołanie do obiektu [Nullable](../nullable/), którego reprezentowana wartość ma być użyta jako druga porównywana wartość |

### Wartość zwracana

True, jeśli porównywane wartości są równe, w przeciwnym razie - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function


Porównuje równościowo dwa inteligentne wskaźniki.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ obiektu wskazywanego przez pierwszy wskaźnik. |
| Y | Typ obiektu wskazywanego przez drugi wskaźnik. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Pierwszy wskaźnik do porównania. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Drugi wskaźnik do porównania. |

### Wartość zwracana

True, jeśli wskaźniki są zgodne, w przeciwnym razie false.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) function


Sprawdza, czy inteligentny wskaźnik jest równy null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ obiektu wskazywanego przez wskaźnik. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | std::nullptr_t | Wskaźnik do sprawdzenia. |

### Wartość zwracana

True, jeśli wskaźnik jest null, w przeciwnym razie false.

## System::operator==(const SmartPtr\<X\>\&, const Y *) function


Porównanie równościowe inteligentnego wskaźnika z prostym wskaźnikiem (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | typ inteligentnego wskaźnika. |
| Y | typ prostego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | inteligentny wskaźnik do porównania (lewy). |
| y | const Y * | wskaźnik do porównania (prawy). |

### Wartość zwracana

True, jeśli wskaźniki są zgodne, w przeciwnym razie false.

## System::operator==(const X *, const SmartPtr\<Y\>\&) function


Porównanie równościowe prostego wskaźnika (C) z inteligentnym wskaźnikiem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | typ prostego wskaźnika. |
| Y | typ inteligentnego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const X * | wskaźnik do porównania (prawy). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | inteligentny wskaźnik do porównania (lewy). |

### Wartość zwracana

True, jeśli wskaźniki są zgodne, w przeciwnym razie false.

## System::operator==(T const\&, std::nullptr_t) function


Sprawdza, czy obiekt typu wartościowego (przetłumaczona struktura C#, itp.) jest równy null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartościowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | T const\& | [Object](../object/) do sprawdzenia. |

### Wartość zwracana

True, jeśli obiekt jest null, false w przeciwnym razie.

## System::operator==(std::nullptr_t, T const\&) function


Sprawdza, czy obiekt typu wartościowego (przetłumaczona struktura C#, itp.) jest równy null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartościowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) do sprawdzenia. |

### Wartość zwracana

True, jeśli obiekt jest null, false w przeciwnym razie.

## System::operator==(Chars\&, const String\&) function


[String](../string/) porównanie.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Chars | [String](../string/) typ literału. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literał do porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

true, jeśli ciągi znaków są zgodne, false w przeciwnym razie.

## System::operator==(T\&, const String\&) function


[String](../string/) porównanie.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [String](../string/) typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | T\& | [String](../string/) wskaźnik do porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

true, jeśli ciągi znaków są zgodne, false w przeciwnym razie.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) function


[Object](../object/) i porównanie z ciągiem znaków.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) do konwersji na ciąg znaków i porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

true, jeśli reprezentacja obiektu jako ciąg znaków jest równa ciągowi, false w przeciwnym razie.

## System::operator==(std::nullptr_t, const String\&) function


Sprawdza, czy ciąg znaków jest równy null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) do sprawdzenia. |

### Wartość zwracana

true, jeśli ciąg znaków jest null, false w przeciwnym razie.

## System::operator==(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function


Określa, czy URI reprezentowane przez bieżący i określony obiekt są równe.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Pierwszy obiekt [Uri](../uri/) do porównania |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Drugi obiekt [Uri](../uri/) do porównania |

### Wartość zwracana

True, jeśli URI są równe, w przeciwnym razie - false

## Zobacz także

* Typedef [SharedPtr](../sharedptr/)
* Klasa [ArraySegment](../arraysegment/)
* Klasa [DateTime](../datetime/)
* Klasa [DateTimeOffset](../datetimeoffset/)
* Klasa [Nullable](../nullable/)
* Klasa [SmartPtr](../smartptr/)
* Klasa [Object](../object/)
* Klasa [String](../string/)
* Klasa [TimeSpan](../timespan/)
* Klasa [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)