---
title: operator<()
second_title: Aspose.Slides C++ API-referencia
description: 
type: docs
weight: 2094
url: /hu/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) függvény




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) függvény




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) függvény


Mindig false értéket ad vissza.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) függvény


Megállapítja, hogy a megadott érték kisebb-e a megadott [Nullable](../nullable/) objektum által képviselt értéknél, a [operator<()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlítandó érték típusa |
| T2 | A második összehasonlítandó értéket képviselő [Nullable](../nullable/) objektum alapvető típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | Az első összehasonlítandóként használandó érték állandó referenciája |
| other | const [Nullable](../nullable/)\<T2\>\& | A [Nullable](../nullable/) objektum állandó referenciája, amelynek képviselt értékét a második összehasonlítandóként kell használni |

### Visszatérési érték

True, ha az első összehasonlítandó kisebb, mint a második összehasonlítandó, egyébként - false

## System::operator<(std::nullptr_t, TimeSpan) függvény




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Lásd még

* Osztály [DateTime](../datetime/)
* Osztály [DateTimeOffset](../datetimeoffset/)
* Osztály [Nullable](../nullable/)
* Osztály [TimeSpan](../timespan/)
* Struktúra [IsNullable](../isnullable/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)