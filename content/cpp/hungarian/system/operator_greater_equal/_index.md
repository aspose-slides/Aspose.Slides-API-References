---
title: operator>=()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 2133
url: /hu/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) függvény




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) függvény




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) függvény


Mindig hamis értékkel tér vissza.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) függvény


Megállapítja, hogy a megadott érték nagyobb vagy egyenlő-e a megadott [Nullable](../nullable/) objektum által képviselt értékkel, az [operator>=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó érték típusa |
| T2 | A [Nullable](../nullable/) objektum alapvető típusa, amely a második összehasonlítandó értéket képviseli |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | Egy állandó hivatkozás az első összehasonlítandó értékre |
| other | const [Nullable](../nullable/)\<T2\>\& | Egy állandó hivatkozás a [Nullable](../nullable/) objektumra, amelynek képviselt értéke a második összehasonlítandó érték |

### Visszatérési érték

Igaz, ha az első összehasonlítandó nagyobb vagy egyenlő a másodikkal, egyébként hamis

## System::operator>=(std::nullptr_t, TimeSpan) függvény




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Lásd még

* Osztály [DateTime](../datetime/)
* Osztály [DateTimeOffset](../datetimeoffset/)
* Osztály [Nullable](../nullable/)
* Osztály [TimeSpan](../timespan/)
* Struktúra [IsNullable](../isnullable/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)