---
title: operator!=()
second_title: Aspose.Slides dla C++ – odniesienie API
description: 
type: docs
weight: 2055
url: /pl/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) funkcja




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) funkcja




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) funkcja




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) funkcja


Określa, czy podany obiekt [Nullable](../nullable/) reprezentuje wartość różną od null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | std::nullptr_t | Stałe odwołanie do obiektu [Nullable](../nullable/) do przetestowania |

### Wartość zwracana

Prawda, jeśli określony obiekt reprezentuje wartość nie-null, w przeciwnym razie fałsz

## System::operator!=(const T1\&, const Nullable\<T2\>\&) funkcja


Określa, czy podana wartość nie jest równa wartości reprezentowanej przez podany obiekt [Nullable](../nullable/) poprzez zastosowanie [operator!=()](./) do tych wartości.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ pierwszej porównywanej wartości |
| T2 | Podstawowy typ obiektu [Nullable](../nullable/), który reprezentuje drugą porównywaną wartość |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| some | const T1\& | Stałe odwołanie do wartości, która ma być użyta jako pierwszy porównywany operand |
| other | const [Nullable](../nullable/)\<T2\>\& | Stałe odwołanie do obiektu [Nullable](../nullable/), którego reprezentowana wartość ma być użyta jako drugi porównywany operand |

### Wartość zwracana

Prawda, jeśli porównywane wartości nie są równe, w przeciwnym razie – fałsz

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) funkcja


Porównanie nierówności dwóch inteligentnych wskaźników.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ wskazywanego obiektu pierwszego wskaźnika. |
| Y | Typ wskazywanego obiektu drugiego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Pierwszy wskaźnik do porównania. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Drugi wskaźnik do porównania. |

### Wartość zwracana

Fałsz, jeśli wskaźniki są takie same, w przeciwnym razie prawda.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) funkcja


Sprawdza, czy inteligentny wskaźnik nie jest nullem.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ wskazywanego obiektu wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Wskaźnik do sprawdzenia. |

### Wartość zwracana

Fałsz, jeśli wskaźnik jest nullem, w przeciwnym razie prawda.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) funkcja


Sprawdza, czy inteligentny wskaźnik nie jest nullem.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ wskazywanego obiektu wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | std::nullptr_t | Wskaźnik do sprawdzenia. |

### Wartość zwracana

Fałsz, jeśli wskaźnik jest nullem, w przeciwnym razie prawda.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) funkcja


Porównanie nierówności inteligentnego wskaźnika z prostym (C) wskaźnikiem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ inteligentnego wskaźnika. |
| Y | Typ prostego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Inteligentny wskaźnik do porównania (lewy). |
| y | const Y * | Wskaźnik do porównania ( prawy). |

### Wartość zwracana

Fałsz, jeśli wskaźniki są takie same, w przeciwnym razie prawda.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) funkcja


Porównanie równości prostego (C) wskaźnika z inteligentnym wskaźnikiem.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ prostego wskaźnika. |
| Y | Typ inteligentnego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const X * | Wskaźnik do porównania (prawy). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Inteligentny wskaźnik do porównania (lewy). |

### Wartość zwracana

Fałsz, jeśli wskaźniki są takie same, w przeciwnym razie prawda.

## System::operator!=(Chars\&, const String\&) funkcja


[String](../string/) porównanie.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Chars | Typ literału [String](../string/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | Chars\& | Literał [String](../string/) do porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

fałsz, jeśli łańcuchy są takie same, w przeciwnym razie prawda.

## System::operator!=(T\&, const String\&) funkcja


[String](../string/) porównanie.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wskaźnika [String](../string/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | T\& | [String](../string/) wskaźnik do porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

fałsz, jeśli łańcuchy są takie same, w przeciwnym razie prawda.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) funkcja


[Object](../object/) i porównanie z łańcuchem znaków.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) do konwersji na łańcuch znaków i porównania. |
| right | const [String](../string/)\& | [String](../string/) do porównania. |

### Wartość zwracana

fałsz, jeśli reprezentacja łańcucha znaków obiektu jest równa łańcuchowi, w przeciwnym razie prawda.

## System::operator!=(std::nullptr_t, const String\&) funkcja


Sprawdza, czy łańcuch znaków jest nullem.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) do sprawdzenia. |

### Wartość zwracana

fałsz, jeśli łańcuch znaków jest nullem, w przeciwnym razie prawda.

## System::operator!=(std::nullptr_t, TimeSpan) funkcja




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) funkcja


Określa, czy URI reprezentowane przez bieżący i określony obiekt nie są równe.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Pierwszy obiekt [Uri](../uri/) do porównania |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Drugi obiekt [Uri](../uri/) do porównania |

### Wartość zwracana

Prawda, jeśli URI nie są równe, w przeciwnym razie – fałsz

## See Also

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