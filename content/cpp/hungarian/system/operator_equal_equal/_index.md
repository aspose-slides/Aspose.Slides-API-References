---
title: operator==()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 2042
url: /hu/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) függvény




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) függvény




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) függvény




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) függvény


Megállapítja, hogy a megadott [Nullable](../nullable/) objektum olyan értéket tartalmaz-e, amely egyenlő a null értékkel.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | std::nullptr_t | Egy állandó referencia egy [Nullable](../nullable/) objektumra a teszthez |

### Visszatérési érték

Igaz, ha a megadott objektum null értéket képvisel, egyébként hamis

## System::operator==(const T1\&, const Nullable\<T2\>\&) függvény


Megállapítja, hogy a megadott érték egyenlő-e a megadott [Nullable](../nullable/) objektum által képviselt értékkel a [operator==()](./) alkalmazásával.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó érték típusa |
| T2 | A [Nullable](../nullable/) objektum mögöttes típusa, amely a második összehasonlítandó értéket képviseli |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | Egy állandó referencia az első összehasonlítandó értékre |
| other | const [Nullable](../nullable/)\<T2\>\& | Egy állandó referencia a [Nullable](../nullable/) objektumra, amelynek képviselt értéke a második összehasonlítandó érték |

### Visszatérési érték

Igaz, ha az összehasonlítandók egyenlőek, egyébként - hamis

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) függvény


Két intelligens mutató egyenlő-összehasonlítása.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Az első mutató mutatott típusa. |
| Y | A második mutató mutatott típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Az első összehasonlítandó mutató. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | A második összehasonlítandó mutató. |

### Visszatérési érték

Igaz, ha a mutatók megegyeznek, hamis egyébként.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) függvény


Ellenőrzi, hogy az intelligens mutató null-e.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | A mutató mutatott típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | std::nullptr_t | A vizsgálandó mutató. |

### Visszatérési érték

Igaz, ha a mutató null, hamis egyébként.

## System::operator==(const SmartPtr\<X\>\&, const Y *) függvény


Intelligens mutató összehasonlítása egyszerű (C) mutatóval.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Az intelligens mutató típusa. |
| Y | Az egyszerű mutató típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Az összehasonlítandó intelligens mutató (bal). |
| y | const Y * | Az összehasonlítandó mutató (jobbra). |

### Visszatérési érték

Igaz, ha a mutatók megegyeznek, hamis egyébként.

## System::operator==(const X *, const SmartPtr\<Y\>\&) függvény


Intelligens mutató összehasonlítása egyszerű (C) mutatóval.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Az egyszerű mutató típusa. |
| Y | Az intelligens mutató típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const X * | Az összehasonlítandó mutató (jobbra). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Az összehasonlítandó intelligens mutató (bal). |

### Visszatérési érték

Igaz, ha a mutatók megegyeznek, hamis egyébként.

## System::operator==(T const\&, std::nullptr_t) függvény


Ellenőrzi, hogy az értéktípusú objektum (C# struktúra stb.) null-e.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | T const\& | A [Object](../object/) ellenőrzésre. |

### Visszatérési érték

Igaz, ha az objektum null, hamis egyébként.

## System::operator==(std::nullptr_t, T const\&) függvény


Ellenőrzi, hogy az értéktípusú objektum (C# struktúra stb.) null-e.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | std::nullptr_t | A [Object](../object/) ellenőrzésre. |

### Visszatérési érték

Igaz, ha az objektum null, hamis egyébként.

## System::operator==(Chars\&, const String\&) függvény


[String](../string/) összehasonlítás.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Chars | [String](../string/) literál típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | Chars\& | A [String](../string/) literál a bal oldalon. |
| right | const [String](../string/)\& | A [String](../string/) a jobb oldalon. |

### Visszatérési érték

true, ha a karakterláncok egyeznek, false egyébként.

## System::operator==(T\&, const String\&) függvény


[String](../string/) összehasonlítás.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [String](../string/) mutatótípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | T\& | [String](../string/) mutató a bal oldalon. |
| right | const [String](../string/)\& | [String](../string/) a jobb oldalon. |

### Visszatérési érték

true, ha a karakterláncok egyeznek, false egyébként.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) függvény


[Object](../object/) és karakterlánc összehasonlítás.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) objektum, amelyet karakterlánccá konvertálunk és összehasonlítunk. |
| right | const [String](../string/)\& | [String](../string/) összehasonlításra. |

### Visszatérési érték

true, ha az objektum karakterláncának reprezentációja megegyezik a karakterlánccal, false egyébként.

## System::operator==(std::nullptr_t, const String\&) függvény


Ellenőrzi, hogy a karakterlánc null-e.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | std::nullptr_t | A [String](../string/) ellenőrzésre. |

### Visszatérési érték

true, ha a karakterlánc null, false egyébként.

## System::operator==(std::nullptr_t, TimeSpan) függvény




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) függvény


Megállapítja, hogy a jelenlegi és a megadott objektum által képviselt URI-k egyenlőek-e.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Az első [Uri](../uri/) objektum a bal oldalon |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | A második [Uri](../uri/) objektum a jobb oldalon |

### Visszatérési érték

True, ha az URI-k egyenlőek, egyébként - false

## Lásd még

* Típusdefiníció [SharedPtr](../sharedptr/)
* Osztály [ArraySegment](../arraysegment/)
* Osztály [DateTime](../datetime/)
* Osztály [DateTimeOffset](../datetimeoffset/)
* Osztály [Nullable](../nullable/)
* Osztály [SmartPtr](../smartptr/)
* Osztály [Object](../object/)
* Osztály [String](../string/)
* Osztály [TimeSpan](../timespan/)
* Osztály [Uri](../uri/)
* Struktúra [IsNullable](../isnullable/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)