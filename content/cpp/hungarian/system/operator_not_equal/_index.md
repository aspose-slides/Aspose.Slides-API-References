---
title: operator!=()
second_title: Aspose.Slides for C++ API referencia
description: 
type: docs
weight: 2055
url: /hu/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) függvény




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) függvény




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) függvény




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) függvény


Megállapítja, hogy a megadott [Nullable](../nullable/) objektum olyan értéket képvisel-e, amely nem egyenlő a null értékkel.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | std::nullptr_t | A konstans hivatkozás egy [Nullable](../nullable/) objektumra a teszteléshez |

### Visszatérési érték

Igaz, ha a megadott objektum nem null értéket képvisel, egyébként hamis

## System::operator!=(const T1\&, const Nullable\<T2\>\&) függvény


Megállapítja, hogy a megadott érték nem egyenlő-e a megadott [Nullable](../nullable/) objektum által képviselt értékkel, a [operator!=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó érték típusa |
| T2 | A [Nullable](../nullable/) objektum alapvető típusa, amely a második összehasonlítandó értéket képviseli |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | A konstans hivatkozás az értékre, amelyet első összehasonlítandóként kell használni |
| other | const [Nullable](../nullable/)\<T2\>\& | A konstans hivatkozás a [Nullable](../nullable/) objektumra, amelynek képviselt értékét második összehasonlítandóként kell használni |

### Visszatérési érték

Igaz, ha a összehasonlítandók nem egyenlőek, egyébként - hamis

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) függvény


Két okos mutató egyenlőtlenség-összehasonlítása.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
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

Hamis, ha a mutatók egyeznek, igaz egyébként.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) függvény


Ellenőrzi, hogy az okos mutató nem null-e.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | A mutató mutatott típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Az ellenőrzendő mutató. |

### Visszatérési érték

Hamis, ha a mutató null, igaz egyébként.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) függvény


Ellenőrzi, hogy az okos mutató nem null-e.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | A mutató mutatott típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | std::nullptr_t | Az ellenőrzendő mutató. |

### Visszatérési érték

Hamis, ha a mutató null, igaz egyébként.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) függvény


Egyenlőtlenségi összehasonlítás okos mutató és egyszerű (C) mutató között.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | az okos mutató típusa. |
| Y | az egyszerű mutató típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | összehasonlítandó okos mutató (bal). |
| y | const Y * | összehasonlítandó mutató (jobb). |

### Visszatérési érték

Hamis, ha a mutatók egyeznek, igaz egyébként.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) függvény


Egyenlőség-összehasonlítás okos mutató és egyszerű (C) mutató között.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | az egyszerű mutató típusa. |
| Y | az okos mutató típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const X * | összehasonlítandó mutató (jobb). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | összehasonlítandó okos mutató (bal). |

### Visszatérési érték

Hamis, ha a mutatók egyeznek, igaz egyébként.

## System::operator!=(Chars\&, const String\&) függvény


[String](../string/) összehasonlítás.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Chars | [String](../string/) literál típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literál a összehasonlításhoz. |
| right | const [String](../string/)\& | [String](../string/) a összehasonlításhoz. |

### Visszatérési érték

hamis, ha a karakterláncok egyeznek, igaz egyébként.

## System::operator!=(T\&, const String\&) függvény


[String](../string/) összehasonlítás.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [String](../string/) mutató típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | T\& | [String](../string/) mutató a összehasonlításhoz. |
| right | const [String](../string/)\& | [String](../string/) a összehasonlításhoz. |

### Visszatérési érték

hamis, ha a karakterláncok egyeznek, igaz egyébként.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) függvény


[Object](../object/) és string összehasonlítás.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) konvertálása stringgé és összehasonlítása. |
| right | const [String](../string/)\& | [String](../string/) összehasonlítása. |

### Visszatérési érték

hamis, ha az objektum string reprezentációja megegyezik a stringgel, igaz egyébként.

## System::operator!=(std::nullptr_t, const String\&) függvény


Ellenőrzi, hogy a string null-e.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) ellenőrzése. |

### Visszatérési érték

hamis, ha a string null, igaz egyébként.

## System::operator!=(std::nullptr_t, TimeSpan) függvény




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) függvény


Megállapítja, hogy a jelenlegi és a megadott objektumok által képviselt URI-k nem egyenlőek-e.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Az első [Uri](../uri/) objektum a összehasonlításhoz |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | A második [Uri](../uri/) objektum a összehasonlításhoz |

### Visszatérési érték

Igaz, ha az URI-k nem egyenlőek, egyébként - hamis

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